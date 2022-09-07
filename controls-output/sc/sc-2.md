---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SC-2 - Application Partitioning
{: #sc-2}

## Requirements
{: #requirements}

The information system separates user functionality (including user interface services) from information system management functionality.

## Control Supplemental Guidance
{: #supplemental-guidance}

Information system management functionality includes, for example, functions necessary to administer databases, network components, workstations, or servers, and typically requires privileged user access. The separation of user functionality from information system management functionality is either physical or logical. Organizations implement separation of system management-related functionality from user functionality by using different computers, different central processing units, different instances of operating systems, different network addresses, virtualization techniques, or combinations of these or other methods, as appropriate. This type of separation includes, for example, web administrative interfaces that use separate authentication methods for users of any other information system resources. Separation of system and user functionality may include isolating administrative interfaces on different domains and with additional access controls.



## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000471: Check that at least # Virtual Private Cloud(VPC)s have been created](https://cloud.ibm.com/security-compliance/goals/3000471?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000472: Check that at least # instances of Transit Gateway have been created](https://cloud.ibm.com/security-compliance/goals/3000472?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
