---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-2 (11) - Remote Access - Separate Device
{: #ia-2.11}

## Requirements
{: #requirements}

The information system implements multifactor authentication for remote access to privileged and non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access and the device meets [FIPS 140-2 level 2 capable or above or equivalent].

## Control Supplemental Guidance
{: #supplemental-guidance}

For remote access to privileged/non-privileged accounts, the purpose of requiring a device that is separate from the information system gaining access for one of the factors during multifactor authentication is to reduce the likelihood of compromising authentication credentials stored on the system. For example, adversaries deploying malicious code on organizational information systems can potentially compromise such credentials resident on the system and subsequently impersonate authorized users.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ia-2.11_prm_1 | FIPS 140-2 level 2 capable or above or equivalent | organization-defined strength of mechanism requirements |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

