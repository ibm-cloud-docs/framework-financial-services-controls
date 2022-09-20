---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 (1) - Password-Based Authentication
{: #ia-5.1}

## Requirements
{: #requirements}

The information system, for password-based authentication:

- \[(a)\] Enforces minimum password complexity of [minimum length of 8 characters, cannot be a derivative of the username, and must have a combination of alpha and numeric characters];

- \[(b)\] Enforces at least the following number of changed characters when new passwords are created: [at least one (1)];

- \[(c)\] Stores and transmits only cryptographically-protected passwords;

- \[(d)\] Enforces password minimum and maximum lifetime restrictions of [require passwords to be changed every 90 days, temporary passwords for web applications only valid for 24 hours];

- \[(e)\] Prohibits password reuse for [twenty-four (24)] generations; and

- \[(f)\] Allows the use of a temporary password for system logons with an immediate change to a permanent password.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)

## NIST supplemental guidance
{: #supplemental-guidance}

This control enhancement applies to single-factor authentication of individuals using passwords as individual or group authenticators, and in a similar manner, when passwords are part of multifactor authenticators. This control enhancement does not apply when passwords are used to unlock hardware authenticators (e.g., Personal Identity Verification cards). The implementation of such password mechanisms may not meet all of the requirements in the enhancement. Cryptographically-protected passwords include, for example, encrypted versions of passwords and one-way cryptographic hashes of passwords. The number of changed characters refers to the number of changes required with respect to the total number of positions in the current password. Password lifetime restrictions do not apply to temporary passwords. To mitigate certain brute force attacks against passwords, organizations may also consider salting passwords.

