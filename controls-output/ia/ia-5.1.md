---

copyright:
  years: 2020, 2022

lastupdated: "2022-11-01"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-5 (1) - Password-based Authentication
{: #ia-5.1}

## Control requirements
{: #control-requirements}

The information system, for password-based authentication:

IA-5 (1) (a)
    : Enforces minimum password complexity of _[[Assignment: organization-defined requirements for case sensitivity, number of characters, mix of upper-case letters, lower-case letters, numbers, and special characters, including minimum requirements for each type]_];

IA-5 (1) (b)
    : Enforces at least the following number of changed characters when new passwords are created: _[[Assignment: organization-defined number]_];

IA-5 (1) (c)
    : Stores and transmits only cryptographically-protected passwords;

IA-5 (1) (d)
    : Enforces password minimum and maximum lifetime restrictions of _[[Assignment: organization-defined numbers for lifetime minimum, lifetime maximum]_];

IA-5 (1) (e)
    : Prohibits password reuse for _[[Assignment: organization-defined number]_] generations; and

IA-5 (1) (f)
    : Allows the use of a temporary password for system logons with an immediate change to a permanent password.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement applies to single-factor authentication of individuals using passwords as individual or group authenticators, and in a similar manner, when passwords are part of multifactor authenticators. This control enhancement does not apply when passwords are used to unlock hardware authenticators (e.g., Personal Identity Verification cards). The implementation of such password mechanisms may not meet all of the requirements in the enhancement. Cryptographically-protected passwords include, for example, encrypted versions of passwords and one-way cryptographic hashes of passwords. The number of changed characters refers to the number of changes required with respect to the total number of positions in the current password. Password lifetime restrictions do not apply to temporary passwords. To mitigate certain brute force attacks against passwords, organizations may also consider salting passwords.





