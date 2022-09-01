---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# IA-4 - Identifier Management
{: #ia-4}

## Requirements
{: #requirements}

The organization manages information system identifiers by:

- \[a.\] Receiving authorization from [organization-defined personnel or roles] to assign an individual, group, role, or device identifier;

- \[b.\] Selecting an identifier that identifies an individual, group, role, or device;

- \[c.\] Assigning the identifier to the intended individual, group, role, or device;

- \[d.\] Preventing reuse of identifiers for [at least two (2) years]; and

- \[e.\] Disabling the identifier after [ninety (90) calendar days for user identifiers].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must follow customer requirements when establishing customer identifiers including:
- aligning with customer email address or unique number corresponding to a user
- prohibiting the use of Social Security Numbers (SSN) or customer-specific identifiers in the organization&#39;s internal environment

## Control Supplemental Guidance
{: #supplemental-guidance}

Common device identifiers include, for example, media access control (MAC), Internet protocol (IP) addresses, or device-unique token identifiers. Management of individual identifiers is not applicable to shared information system accounts (e.g., guest and anonymous accounts). Typically, individual identifiers are the user names of the information system accounts assigned to those individuals. In such instances, the account management activities of AC-2 use account names provided by IA-4. This control also addresses individual identifiers not necessarily associated with information system accounts (e.g., identifiers used in physical security control databases accessed by badge reader systems for access to information systems). Preventing reuse of identifiers implies preventing the assignment of previously used individual, group, role, or device identifiers to different individuals, groups, roles, or devices.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ia-4_prm_1 |  | organization-defined personnel or roles |
| ia-4_prm_2 | at least two (2) years | organization-defined time period |
| ia-4_prm_3 | ninety (90) calendar days for user identifiers | organization-defined time period of inactivity |