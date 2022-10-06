---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-06"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SC-7 (10) - Prevent Unauthorized Exfiltration
{: #sc-7.10}

## Control requirements
{: #control-requirements}

SC-7 (10) - 0
    : The organization prevents the unauthorized exfiltration of information across managed interfaces.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Accessing the public internet](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-internet)
- [Connecting application provider to the management VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-management)
- [Connectivity to {{site.data.keyword.cloud_notm}} services with private endpoints](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-to-ibm-services)
- [Consumer connectivity to workload VPC](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-workload)
- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000406: Check whether Virtual Private Cloud (VPC) has no rules in the default security group 
- 3000412: Check whether all virtual server instances have at least one Virtual Private Cloud (VPC) security group attached 
- 3000413: Check whether all network interfaces of a virtual server instance have at least one Virtual Private Cloud (VPC) security group attached 
- 3000418: Check whether account has at least one VPN or Direct Link configured 
- 3000444: Check whether Security Groups for VPC contains no outbound rules in security groups that specify source IP 8.8.8.8/32 to DNS port 
- 3000447: Check whether Virtual Private Cloud (VPC) classic access is disabled 
- 3000448: Check whether Virtual Private Cloud (VPC) has no public gateways attached at the time of provisioning 
- 3000449: Check whether Virtual Private Cloud (VPC) has no public gateways attached 
- 3000452: Check whether Virtual Private Cloud (VPC) network access control lists should allow egress to any ports that are open only to permitted IPs 
- 3000453: Check whether Virtual Servers for VPC instance has the minimum # interfaces 
- 3000467: Check whether Virtual Private Cloud (VPC) has no subnet with public gateway attached 
- 3000468: Check whether Virtual Private Cloud (VPC) is configured with public gateways that are provisionable only within permitted zones 
- 3000476: Check whether Virtual Private Cloud (VPC) security groups have outbound ports that are open only to permitted IPs

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Safeguards implemented by organizations to prevent unauthorized exfiltration of information from information systems include, for example: (i) strict adherence to protocol formats; (ii) monitoring for beaconing from information systems; (iii) monitoring for steganography; (iv) disconnecting external network interfaces except when explicitly needed; (v) disassembling and reassembling packet headers; and (vi) employing traffic profile analysis to detect deviations from the volume/types of traffic expected within organizations or call backs to command and control centers. Devices enforcing strict adherence to protocol formats include, for example, deep packet inspection firewalls and XML gateways. These devices verify adherence to protocol formats and specification at the application layer and serve to identify vulnerabilities that cannot be detected by devices operating at the network or transport layers. This control enhancement is closely associated with cross-domain solutions and system guards enforcing information flow requirements.





