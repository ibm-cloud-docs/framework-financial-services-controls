---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AU-5 - Response to Audit Logging Process Failures
{: #au-5}

## Control requirements
{: #control-requirements}



### AU-5 (a)


Alert _[Assignment: organization-defined personnel or roles]_ within _[Assignment: organization-defined time period]_ in the event of an audit logging process failure.


### AU-5 (b)


Take the following additional actions: _[IBM Assignment: overwrite oldest record]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The status of all security audit log sources must be monitored for integrity and functionality as designed, at least hourly, and following policy changes, patch updates, and changes.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)


- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit logging process failures include software and hardware errors, failures in audit log capturing mechanisms, and reaching or exceeding audit log storage capacity. Organization-defined actions include overwriting oldest audit records, shutting down the system, and stopping the generation of audit records. Organizations may choose to define additional actions for audit logging process failures based on the type of failure, the location of the failure, the severity of the failure, or a combination of such factors. When the audit logging process failure is related to storage, the response is carried out for the audit log storage repository (i.e., the distinct system component where the audit logs are stored), the system on which the audit logs reside, the total audit log storage capacity of the organization (i.e., all audit log storage repositories combined), or all three. Organizations may decide to take no additional actions after alerting designated roles or personnel.
