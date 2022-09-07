---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# IA-3 - Device Identification And Authentication
{: #ia-3}

## Requirements
{: #requirements}

The information system uniquely identifies and authenticates [all devices] before establishing a [network] connection.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

All devices must be authorized by organization security prior to allowing such network connections.

## Control Supplemental Guidance
{: #supplemental-guidance}

Organizational devices requiring unique device-to-device identification and authentication may be defined by type, by device, or by a combination of type/device. Information systems typically use either shared known information (e.g., Media Access Control [MAC] or Transmission Control Protocol/Internet Protocol [TCP/IP] addresses) for device identification or organizational authentication solutions (e.g., IEEE 802.1x and Extensible Authentication Protocol [EAP], Radius server with EAP-Transport Layer Security [TLS] authentication, Kerberos) to identify/authenticate devices on local and/or wide area networks. Organizations determine the required strength of authentication mechanisms by the security categories of information systems. Because of the challenges of applying this control on large scale, organizations are encouraged to only apply the control to those limited number (and type) of devices that truly need to support this capability.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ia-3_prm_1 | all devices | organization-defined specific and/or types of devices |
| ia-3_prm_2 | network | Choose one or more: local; remote; network |


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000020: Check whether authorized IP ranges are configured for the account](https://cloud.ibm.com/security-compliance/goals/3000020?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000076: IBM Cloud VPC uniquely identifies all physical devices before accepting a network connection](https://cloud.ibm.com/security-compliance/goals/3000076?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
