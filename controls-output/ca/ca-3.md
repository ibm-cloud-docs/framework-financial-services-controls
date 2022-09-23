---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-23"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CA-3 - System Interconnections
{: #ca-3}

## Requirements
{: #requirements}

The organization:

(a) Authorizes connections from the information system to other information systems through the use of Interconnection Security Agreements;

(b) Documents, for each interconnection, the interface characteristics, security requirements, and the nature of the information communicated; and

(c) Reviews and updates Interconnection Security Agreements [at least annually and on input from the customer].

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000045: Check whether the Financial Services Validated setting is enabled in account settings

| Requirement | Goals |
|-------------|-------|
| Part a | - 3000047: Check whether provisioned services are IAM enabled | 
{: caption="Goals for CA-3" caption-side="top"}

## NIST supplemental guidance
{: #supplemental-guidance}

This control applies to dedicated connections between information systems (i.e., system interconnections) and does not apply to transitory, user-controlled connections such as email and website browsing. Organizations carefully consider the risks that may be introduced when information systems are connected to other systems with different security requirements and security controls, both within organizations and external to organizations. Authorizing officials determine the risk associated with information system connections and the appropriate controls employed. If interconnecting systems have the same authorizing official, organizations do not need to develop Interconnection Security Agreements. Instead, organizations can describe the interface characteristics between those interconnecting systems in their respective security plans. If interconnecting systems have different authorizing officials within the same organization, organizations can either develop Interconnection Security Agreements or describe the interface characteristics between systems in the security plans for the respective systems. Organizations may also incorporate Interconnection Security Agreement information into formal contracts, especially for interconnections established between federal agencies and nonfederal (i.e., private sector) organizations. Risk considerations also include information systems sharing the same networks. For certain technologies (e.g., space, unmanned aerial vehicles, and medical devices), there may be specialized connections in place during preoperational testing. Such connections may require Interconnection Security Agreements and be subject to additional security controls.

