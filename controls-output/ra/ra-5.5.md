---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# RA-5(5) - Privileged Access
{: #ra-5.5}

## Requirements
{: #requirements}

The information system implements privileged access authorization to [operating systems, databases, container images, and web applications] for selected [vulnerability scans].

## Control Supplemental Guidance
{: #supplemental-guidance}

In certain situations, the nature of the vulnerability scanning may be more intrusive or the information system component that is the subject of the scanning may contain highly sensitive information. Privileged access authorization to selected system components facilitates more thorough vulnerability scanning and also protects the sensitive nature of such scanning.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ra-5.5_prm_1 | operating systems, databases, container images, and web applications | organization-identified information system components |
| ra-5.5_prm_2 | vulnerability scans | organization-defined vulnerability scanning activities |