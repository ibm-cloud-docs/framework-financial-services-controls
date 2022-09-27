---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# SC-8 (1) - Cryptographic Or Alternate Physical Protection
{: #sc-8.1}

## Requirements
{: #requirements}

The information system implements cryptographic mechanisms to _[prevent unauthorized disclosure of information, highest financial institution standard (FIPS140-2 L3) for Highly Restricted Confidential Information (HRCI)]_ during transmission unless otherwise protected by _[none]_.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- The organization must encrypt customer data in transit regardless of the transport mechanism and/or digital media type used. For web-based applications, the organization will ensure that transmitted data is protected in accordance with the recommendations of the Open Web Application Security Project (OWASP).

## NIST supplemental guidance
{: #supplemental-guidance}

Encrypting information for transmission protects information from unauthorized disclosure and modification. Cryptographic mechanisms implemented to protect information integrity include, for example, cryptographic hash functions which have common application in digital signatures, checksums, and message authentication codes. Alternative physical security safeguards include, for example, protected distribution systems.



