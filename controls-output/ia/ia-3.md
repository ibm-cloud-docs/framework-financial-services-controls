---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-29"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-3 - Device Identification and Authentication
{: #ia-3}

## Control requirements
{: #control-requirements}

IA-3 - 0
    : The information system uniquely identifies and authenticates [organization-defined specific and/or types of devices] before establishing a [local; remote; network] connection.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- All devices must be authorized by organization security prior to allowing such network connections.

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000020: Check whether authorized IP ranges are configured for the account 
- 3000076: IBM Cloud VPC uniquely identifies all physical devices before accepting a network connection

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Organizational devices requiring unique device-to-device identification and authentication may be defined by type, by device, or by a combination of type/device. Information systems typically use either shared known information (e.g., Media Access Control [MAC] or Transmission Control Protocol/Internet Protocol [TCP/IP] addresses) for device identification or organizational authentication solutions (e.g., IEEE 802.1x and Extensible Authentication Protocol [EAP], Radius server with EAP-Transport Layer Security [TLS] authentication, Kerberos) to identify/authenticate devices on local and/or wide area networks. Organizations determine the required strength of authentication mechanisms by the security categories of information systems. Because of the challenges of applying this control on large scale, organizations are encouraged to only apply the control to those limited number (and type) of devices that truly need to support this capability.



