---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# AC-4 (5) - Embedded Data Types
{: #ac-4.5}

## Control requirements
{: #control-requirements}

The information system enforces _[organization-defined limitations]_ on embedding data types within other data types.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- This control is required for ISVs; This control is NOT required for IBM Cloud Platform at this time (bank risk accepted for IBM)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Embedding data types within other data types may result in reduced flow control effectiveness. Data type embedding includes, for example, inserting executable files as objects within word processing files, inserting references or descriptive information into a media file, and compressed or archived data types that may include multiple embedded data types. Limitations on data type embedding consider the levels of embedding and prohibit levels of data type embedding that are beyond the capability of the inspection tools.



