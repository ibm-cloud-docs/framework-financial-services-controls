---

copyright:
  years: 2020, 2023

lastupdated: "2023-03-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-4 - Identifier Management
{: #ia-4}

## Control requirements
{: #control-requirements}

The organization manages information system identifiers by:

IA-4 (a)
    : Receiving authorization from _[Assignment: organization-defined personnel or roles]_ to assign an individual, group, role, or device identifier;

IA-4 (b)
    : Selecting an identifier that identifies an individual, group, role, or device;

IA-4 (c)
    : Assigning the identifier to the intended individual, group, role, or device;

IA-4 (d)
    : Preventing reuse of identifiers for _[IBM Assignment: at least two (2) years]_; and

IA-4 (e)
    : Disabling the identifier after _[IBM Assignment: ninety (90) calendar days for user identifiers]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The organization must follow customer requirements when establishing customer identifiers including:
- aligning with customer email address or unique number corresponding to a user
- prohibiting the use of Social Security Numbers (SSN) or customer-specific identifiers in the organization's internal environment

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Rules |
|----------------|-------|
| IA-4 (b) | - IBM Cloud assigns identifiers that identify individuals, groups, roles, and devices \n - Check whether Virtual Servers for VPC instances are identifable by the workload they are running based on the Auto Scale for VPC instance group definition \n - Check whether Application Load Balancer for VPC has application port of the workload that is identifiable by the Auto Scale for VPC instance group definition \n - IBMid selects and assigns identifiers that identify individuals \n - Check whether Application Load Balancer for VPC has subnet identifiers of the workload that are identifiable by the Auto Scale for VPC instance group definition | 
| IA-4 (c) | - IBM Cloud assigns identifiers that identify individuals, groups, roles, and devices \n - Check whether Virtual Servers for VPC instances are identifable by the workload they are running based on the Auto Scale for VPC instance group definition \n - Check whether Application Load Balancer for VPC has application port of the workload that is identifiable by the Auto Scale for VPC instance group definition \n - IBMid selects and assigns identifiers that identify individuals \n - Check whether Application Load Balancer for VPC has subnet identifiers of the workload that are identifiable by the Auto Scale for VPC instance group definition | 
| IA-4 (d) | - IBM Cloud prevents reuse of identifiers | 
{: caption="Rules for IA-4 in IBM Cloud for Financial Services v1.1.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Common device identifiers include, for example, media access control (MAC), Internet protocol (IP) addresses, or device-unique token identifiers. Management of individual identifiers is not applicable to shared information system accounts (e.g., guest and anonymous accounts). Typically, individual identifiers are the user names of the information system accounts assigned to those individuals. In such instances, the account management activities of AC-2 use account names provided by IA-4. This control also addresses individual identifiers not necessarily associated with information system accounts (e.g., identifiers used in physical security control databases accessed by badge reader systems for access to information systems). Preventing reuse of identifiers implies preventing the assignment of previously used individual, group, role, or device identifiers to different individuals, groups, roles, or devices.





