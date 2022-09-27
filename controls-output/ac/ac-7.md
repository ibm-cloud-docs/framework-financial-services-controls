---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# AC-7 - Unsuccessful Logon Attempts
{: #ac-7}

## Requirements
{: #requirements}

The information system:

- (a) Enforces a limit of _[not more than five (5)]_ consecutive invalid logon attempts by a user during a _[fifteen (15) minutes]_; and
- (b) Automatically _[locks the account/node for a thirty (30) minutes]_ when the maximum number of unsuccessful attempts is exceeded.

## NIST supplemental guidance
{: #supplemental-guidance}

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by information systems are usually temporary and automatically release after a predetermined time period established by organizations. If a delay algorithm is selected, organizations may choose to employ different algorithms for different information system components based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at both the operating system and the application levels.



