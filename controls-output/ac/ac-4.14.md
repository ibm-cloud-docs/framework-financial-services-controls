---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-07"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AC-4 (14) - Security Policy Filter Constraints
{: #ac-4.14}

## Requirements
{: #requirements}

The information system, when transferring information between different security domains, implements [organization-defined security policy filters] requiring fully enumerated formats that restrict data structure and content.

## Control Additional FS Cloud Specifications
{: #additional-fs-cloud-specifications}

This control is required for ISVs; This control is NOT required for IBM Cloud Platform at this time (bank risk accepted for IBM)

## Control Supplemental Guidance
{: #supplemental-guidance}

Data structure and content restrictions reduce the range of potential malicious and/or unsanctioned content in cross-domain transactions. Security policy filters that restrict data structures include, for example, restricting file sizes and field lengths. Data content policy filters include, for example: (i) encoding formats for character sets (e.g., Universal Character Set Transformation Formats, American Standard Code for Information Interchange); (ii) restricting character data fields to only contain alpha-numeric characters; (iii) prohibiting special characters; and (iv) validating schema structures.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ac-4.14_prm_1 |  | organization-defined security policy filters |


