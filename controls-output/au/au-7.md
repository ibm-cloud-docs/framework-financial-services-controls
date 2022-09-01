---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AU-7 - Audit Reduction And Report Generation
{: #au-7}

## Requirements
{: #requirements}

The information system provides an audit reduction and report generation capability that:

- \[a.\] Supports on-demand audit review, analysis, and reporting requirements and after-the-fact investigations of security incidents; and

- \[b.\] Does not alter the original content or time ordering of audit records.

## Control Supplemental Guidance
{: #supplemental-guidance}

Audit reduction is a process that manipulates collected audit information and organizes such information in a summary format that is more meaningful to analysts. Audit reduction and report generation capabilities do not always emanate from the same information system or from the same organizational entities conducting auditing activities. Audit reduction capability can include, for example, modern data mining techniques with advanced data filters to identify anomalous behavior in audit records. The report generation capability provided by the information system can generate customizable reports. Time ordering of audit records can be a significant issue if the granularity of the timestamp in the record is insufficient.
