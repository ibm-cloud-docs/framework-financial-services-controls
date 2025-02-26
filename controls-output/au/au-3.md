---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AU-3 - Content of Audit Records
{: #au-3}

## Control requirements
{: #control-requirements}



### AU-3 - 0


Ensure that audit records contain information that establishes the following:
a. What type of event occurred;
b. When the event occurred;
c. Where the event occurred;
d. Source of the event;
e. Outcome of the event; and
f. Identity of any individuals, subjects, or objects/entities associated with the event.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The following events are to be audited within the system:
- The identity of the account accessing the system, e.g., standard accounts, secondary accounts, external accounts, service accounts.
- Date and local time zone (or UTC)
- Authentication method, examples include but are not limited to SSO, mainframe, etc.
System name generating the log
- Log recording system name
- Source IP address
- Port, where available
- Protocol, where available
- Session duration, where available
- Session Identification, where available
- Cookie session identification value modification, where available

In some cases, legal, compliance or business reasons may result in the need for additional security audit logging attributes for a given system. Please refer to the customer for more information/requirements.

Validate audit/log files contain the necessary information the customer requires to meet policy/regulatory requirements.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Audit logging of {{site.data.keyword.cloud_notm}} events](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit)


- [Audit logging of application provider events and SIEM](/docs/framework-financial-services?topic=framework-financial-services-shared-logging-audit-provider)


- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Audit record content that may be necessary to support the auditing function includes event descriptions (item a), time stamps (item b), source and destination addresses (item c), user or process identifiers (items d and f), success or fail indications (item e), and filenames involved (items a, c, e, and f) . Event outcomes include indicators of event success or failure and event-specific results, such as the system security and privacy posture after the event occurred. Organizations consider how audit records can reveal information about individuals that may give rise to privacy risks and how best to mitigate such risks. For example, there is the potential to reveal personally identifiable information in the audit trail, especially if the trail records inputs or is based on patterns or time of usage.
