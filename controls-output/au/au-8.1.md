---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-02"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# AU-8 (1) - Synchronization With Authoritative Time Source
{: #au-8.1}

## Requirements
{: #requirements}

The information system:

- \[(a)\] Compares the internal information system clocks [authoritative time source: servertime.service.softlayer.com] with [at least hourly]; and

- \[(b)\] Synchronizes the internal system clocks to the authoritative time source when the time difference is greater than [organization-defined time period].

## Control Supplemental Guidance
{: #supplemental-guidance}

This control enhancement provides uniformity of time stamps for information systems with multiple system clocks and systems connected over a network.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| au-8.1_prm_1 | authoritative time source: servertime.service.softlayer.com | organization-defined frequency |
| au-8.1_prm_2 | at least hourly | organization-defined authoritative time source |
| au-8.1_prm_3 |  | organization-defined time period |

