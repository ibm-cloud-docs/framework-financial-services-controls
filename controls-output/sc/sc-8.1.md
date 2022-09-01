---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SC-8(1) - Cryptographic Or Alternate Physical Protection
{: #sc-8.1}

## Requirements
{: #requirements}

The information system implements cryptographic mechanisms to [prevent unauthorized disclosure of information, highest financial institution standard (FIPS140-2 L3) for Highly Restricted Confidential Information (HRCI)] during transmission unless otherwise protected by [none].

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).

## Control Supplemental Guidance
{: #supplemental-guidance}

Encrypting information for transmission protects information from unauthorized disclosure and modification. Cryptographic mechanisms implemented to protect information integrity include, for example, cryptographic hash functions which have common application in digital signatures, checksums, and message authentication codes. Alternative physical security safeguards include, for example, protected distribution systems.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-8.1_prm_1 | prevent unauthorized disclosure of information, highest financial institution standard (FIPS140-2 L3) for Highly Restricted Confidential Information (HRCI) | Choose one or more: prevent unauthorized disclosure of information; detect changes to information |
| sc-8.1_prm_2 | none | organization-defined alternative physical safeguards |