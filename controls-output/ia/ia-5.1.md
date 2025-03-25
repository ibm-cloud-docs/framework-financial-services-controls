---
copyright:
  years: 2020, 2025

lastupdated: "2025-03-11"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 (1) -  Password-based Authentication
{: #ia-5.1}

## Control requirements
{: #control-requirements}



### IA-5 (1) (a)


For password-based authentication:
Maintain a list of commonly-used, expected, or compromised passwords and update the list _[Assignment: organization-defined frequency]_ and when organizational passwords are suspected to have been compromised directly or indirectly.

### IA-5 (1) (b)


For password-based authentication:
Verify, when users create or update passwords, that the passwords are not found on the list of commonly-used, expected, or compromised passwords in IA-5(1)(a).


### IA-5 (1) (c)


For password-based authentication:
Transmit passwords only over cryptographically-protected channels.


### IA-5 (1) (d)


For password-based authentication:
Store passwords using an approved salted key derivation function, preferably using a keyed hash.


### IA-5 (1) (e)


For password-based authentication:
Require immediate selection of a new password upon account recovery.


### IA-5 (1) (f)


For password-based authentication:
Allow user selection of long passwords and passphrases, including spaces and all printable characters.


### IA-5 (1) (g)


The information system, for password-based authentication:
Employ automated tools to assist the user in selecting strong password authenticators.


### IA-5 (1) (h)


The information system, for password-based authentication:
Enforce the following composition and complexity rules: _[IBM Assignment: minimum length of 8 characters, cannot be a derivative of the username, and must have a combination of alpha and numeric characters]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Temporary passwords for web applications should only be valid for 24 hours.

At least one (1) character change should be enforced when new passwords are created.

Password reuse should be prohibited for ten (10) generations.







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Password-based authentication applies to passwords regardless of whether they are used in single-factor or multi-factor authentication. Long passwords or passphrases are preferable over shorter passwords. Enforced composition rules provide marginal security benefits while decreasing usability. However, organizations may choose to establish certain rules for password generation (e.g., minimum character length for long passwords) under certain circumstances and can enforce this requirement in IA-5(1)(h). Account recovery can occur, for example, in situations when a password is forgotten. Cryptographically protected passwords include salted one-way cryptographic hashes of passwords. The list of commonly used, compromised, or expected passwords includes passwords obtained from previous breach corpuses, dictionary words, and repetitive or sequential characters. The list includes context-specific words, such as the name of the service, username, and derivatives thereof.
