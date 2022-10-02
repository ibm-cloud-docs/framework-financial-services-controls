---

copyright:
  years: 2020, 2022

lastupdated: "2022-10-02"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-2 (11) - Remote Access - Separate Device
{: #ia-2.11}

## Control requirements
{: #control-requirements}

IA-2 (11) - 0
    : The information system implements multifactor authentication for remote access to privileged and non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access and the device meets [FIPS 140-2 level 2 capable or above or equivalent].

## NIST supplemental guidance
{: #nist-supplemental-guidance}

For remote access to privileged/non-privileged accounts, the purpose of requiring a device that is separate from the information system gaining access for one of the factors during multifactor authentication is to reduce the likelihood of compromising authentication credentials stored on the system. For example, adversaries deploying malicious code on organizational information systems can potentially compromise such credentials resident on the system and subsequently impersonate authorized users.



