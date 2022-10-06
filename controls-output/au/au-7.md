---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-06"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# AU-7 - Audit Reduction and Report Generation
{: #au-7}

## Control requirements
{: #control-requirements}

The information system provides an audit reduction and report generation capability that:

AU-7 (a)
    : Supports on-demand audit review, analysis, and reporting requirements and after-the-fact investigations of security incidents; and

AU-7 (b)
    : Does not alter the original content or time ordering of audit records.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)
- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)
- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit reduction is a process that manipulates collected audit information and organizes such information in a summary format that is more meaningful to analysts. Audit reduction and report generation capabilities do not always emanate from the same information system or from the same organizational entities conducting auditing activities. Audit reduction capability can include, for example, modern data mining techniques with advanced data filters to identify anomalous behavior in audit records. The report generation capability provided by the information system can generate customizable reports. Time ordering of audit records can be a significant issue if the granularity of the timestamp in the record is insufficient.





