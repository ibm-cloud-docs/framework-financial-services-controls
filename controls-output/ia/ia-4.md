---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# IA-4 - Identifier Management
{: #ia-4}

## Control requirements
{: #control-requirements}

The organization manages information system identifiers by:

- (a) Receiving authorization from _[organization-defined personnel or roles]_ to assign an individual, group, role, or device identifier;
- (b) Selecting an identifier that identifies an individual, group, role, or device;
- (c) Assigning the identifier to the intended individual, group, role, or device;
- (d) Preventing reuse of identifiers for _[at least two (2) years]_; and
- (e) Disabling the identifier after _[ninety (90) calendar days for user identifiers]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

The organization must follow customer requirements when establishing customer identifiers including:
- aligning with customer email address or unique number corresponding to a user
- prohibiting the use of Social Security Numbers (SSN) or customer-specific identifiers in the organization&#39;s internal environment

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement | Goals |
|-------------|-------|
| Part b | - 3000062: IBMid selects and assigns identifiers that identify individuals \n - 3000063: IBM Cloud assigns identifiers that identify individuals, groups, roles, and devices \n - 3000463: Check whether Virtual Servers for VPC instances are identifable by the workload they are running based on the Auto Scale for VPC instance group definition \n - 3000464: Check whether Application Load Balancer for VPC has application port of the workload that is identifiable by the Auto Scale for VPC instance group definition \n - 3000465: Check whether Application Load Balancer for VPC has subnet identifiers of the workload that are identifiable by the Auto Scale for VPC instance group definition | 
| Part c | - 3000062: IBMid selects and assigns identifiers that identify individuals \n - 3000063: IBM Cloud assigns identifiers that identify individuals, groups, roles, and devices \n - 3000463: Check whether Virtual Servers for VPC instances are identifable by the workload they are running based on the Auto Scale for VPC instance group definition \n - 3000464: Check whether Application Load Balancer for VPC has application port of the workload that is identifiable by the Auto Scale for VPC instance group definition \n - 3000465: Check whether Application Load Balancer for VPC has subnet identifiers of the workload that are identifiable by the Auto Scale for VPC instance group definition | 
| Part d | - 3000064: IBM Cloud prevents reuse of identifiers | 
{: caption="Goals for IA-4 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Common device identifiers include, for example, media access control (MAC), Internet protocol (IP) addresses, or device-unique token identifiers. Management of individual identifiers is not applicable to shared information system accounts (e.g., guest and anonymous accounts). Typically, individual identifiers are the user names of the information system accounts assigned to those individuals. In such instances, the account management activities of AC-2 use account names provided by IA-4. This control also addresses individual identifiers not necessarily associated with information system accounts (e.g., identifiers used in physical security control databases accessed by badge reader systems for access to information systems). Preventing reuse of identifiers implies preventing the assignment of previously used individual, group, role, or device identifiers to different individuals, groups, roles, or devices.



