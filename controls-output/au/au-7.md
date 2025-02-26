---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AU-7 - Audit Record Reduction and Report Generation
{: #au-7}

## Control requirements
{: #control-requirements}



### AU-7 (a)


Provide and implement an audit record reduction and report generation capability that:
Supports on-demand audit record review, analysis, and reporting requirements and after-the-fact investigations of incidents.


### AU-7 (b)


Provide and implement an audit record reduction and report generation capability that:
Does not alter the original content or time ordering of audit records.









## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)


- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit record reduction is a process that manipulates collected audit log information and organizes it into a summary format that is more meaningful to analysts. Audit record reduction and report generation capabilities do not always emanate from the same system or from the same organizational entities that conduct audit logging activities. The audit record reduction capability includes modern data mining techniques with advanced data filters to identify anomalous behavior in audit records. The report generation capability provided by the system can generate customizable reports. Time ordering of audit records can be an issue if the granularity of the timestamp in the record is insufficient.
