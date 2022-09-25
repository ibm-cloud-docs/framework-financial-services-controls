---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-25"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# SC-2 - Application Partitioning
{: #sc-2}

## Requirements
{: #requirements}

The information system separates user functionality (including user interface services) from information system management functionality.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000471: Check that at least # Virtual Private Cloud(VPC)s have been created 
- 3000472: Check that at least # instances of Transit Gateway have been created

## NIST supplemental guidance
{: #supplemental-guidance}

Information system management functionality includes, for example, functions necessary to administer databases, network components, workstations, or servers, and typically requires privileged user access. The separation of user functionality from information system management functionality is either physical or logical. Organizations implement separation of system management-related functionality from user functionality by using different computers, different central processing units, different instances of operating systems, different network addresses, virtualization techniques, or combinations of these or other methods, as appropriate. This type of separation includes, for example, web administrative interfaces that use separate authentication methods for users of any other information system resources. Separation of system and user functionality may include isolating administrative interfaces on different domains and with additional access controls.



