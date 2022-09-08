---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-7 - Boundary Protection
{: #sc-7}

## Requirements
{: #requirements}

The information system:

- a. Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

- b. Implements subnetworks for publicly accessible system components that are [physically; logically] separated from internal organizational networks; and

- c. Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization &#34;service delivery&#34; and &#34;corporate&#34; environments must be maintained as separate environments. That is, clear physical and/or logical boundaries separating the two environments must exist.

## Control Supplemental Guidance
{: #supplemental-guidance}

Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks). Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational information systems includes, for example, restricting external web traffic to designated web servers within managed interfaces and prohibiting external traffic that appears to be spoofing internal addresses. Organizations consider the shared nature of commercial telecommunications services in the implementation of security controls associated with the use of such services. Commercial telecommunications services are commonly based on network components and consolidated management systems shared by all attached commercial customers, and may also include third party-provided access lines and other service elements. Such transmission services may represent sources of increased risk despite contract security provisions.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-7_prm_1 |  | Choose : physically; logically |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

