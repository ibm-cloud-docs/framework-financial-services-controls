---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# RA-5 (2) - Update By Frequency / Prior To New Scan / When Identified
{: #ra-5.2}

## Requirements
{: #requirements}

The organization updates the information system vulnerabilities scanned _[prior to a new scan]_.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ra-5.2_prm_1 | prior to a new scan | Choose one or more: organization-defined frequency; prior to a new scan; when new vulnerabilities are identified and reported |
| ra-5.2_prm_2 |  | organization-defined frequency |

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000601: Check whether Container Registry Vulnerability Advisor scans for critical or high vulnerabilities in the system at least every # day(s) 
- 3000611: Check whether Container Registry Vulnerability Advisor scans images for OS vulnerability detection

