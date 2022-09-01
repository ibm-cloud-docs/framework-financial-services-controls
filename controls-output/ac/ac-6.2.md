---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-6 (2) - Non-Privileged Access For Nonsecurity Functions
{: #ac-6.2}

## Requirements
{: #requirements}

The organization requires that users of information system accounts, or roles, with access to [all security functions], use non-privileged accounts or roles, when accessing nonsecurity functions.

## Control Supplemental Guidance
{: #supplemental-guidance}

This control enhancement limits exposure when operating from within privileged accounts or roles. The inclusion of roles addresses situations where organizations implement access control policies such as role-based access control and where a change of role provides the same degree of assurance in the change of access authorizations for both the user and all processes acting on behalf of the user as would be provided by a change between a privileged and non-privileged account.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-6.2_prm_1 | all security functions | organization-defined security functions or security-relevant information |