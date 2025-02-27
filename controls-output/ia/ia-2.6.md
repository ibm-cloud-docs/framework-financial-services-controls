---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-2 (6) -  Access to Accounts — Separate Device
{: #ia-2.6}

## Control requirements
{: #control-requirements}



### IA-2 (6) (a)


Implement multi-factor authentication for _[IBM Assignment: local, network and remote]_ access to _[IBM Assignment: privileged accounts; non-privileged accounts]_ such that:
One of the factors is provided by a device separate from the system gaining access.


### IA-2 (6) (b)


Implement multi-factor authentication for _[IBM Assignment: local, network and remote]_ access to _[IBM Assignment: privileged accounts; non-privileged accounts]_ such that:
The device meets _[IBM Assignment: FIPS 140-2 level 2 capable or above or equivalent]_.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

The purpose of requiring a device that is separate from the system to which the user is attempting to gain access for one of the factors during multi-factor authentication is to reduce the likelihood of compromising authenticators or credentials stored on the system. Adversaries may be able to compromise such authenticators or credentials and subsequently impersonate authorized users. Implementing one of the factors on a separate device (e.g., a hardware token), provides a greater strength of mechanism and an increased level of assurance in the authentication process.
