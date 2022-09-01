---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AU-3 - Content Of Audit Records
{: #au-3}

## Requirements
{: #requirements}

The information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

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

## Control Supplemental Guidance
{: #supplemental-guidance}

Audit record content that may be necessary to satisfy the requirement of this control, includes, for example, time stamps, source and destination addresses, user/process identifiers, event descriptions, success/fail indications, filenames involved, and access control or flow control rules invoked. Event outcomes can include indicators of event success or failure and event-specific results (e.g., the security state of the information system after the event occurred).
