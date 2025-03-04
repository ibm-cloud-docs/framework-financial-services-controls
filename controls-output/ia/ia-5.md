---
copyright:
  years: 2020, 2025

lastupdated: "2025-03-04"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 - Authenticator Management
{: #ia-5}

## Control requirements
{: #control-requirements}



### IA-5 (a)


Manage system authenticators by:
Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, service, or device receiving the authenticator.


### IA-5 (b)


Manage system authenticators by:
Establishing initial authenticator content for any authenticators issued by the organization.


### IA-5 (c)


Manage system authenticators by:
Ensuring that authenticators have sufficient strength of mechanism for their intended use.


### IA-5 (d)


Manage system authenticators by:
Establishing and implementing administrative procedures for initial authenticator distribution, for lost or compromised or damaged authenticators, and for revoking authenticators.


### IA-5 (e)


Manage system authenticators by:
Changing default authenticators prior to first use.


### IA-5 (f)

Manage system authenticators by:
Changing or refreshing authenticators _[IBM Assignment: 90 days for user passwords and 365 days for system-to-system authenticators]_ or when _[IBM Assignment: enforce password change or refresh when a known compromise has occurred]_ occur.


### IA-5 (g)


Manage system authenticators by:
Protecting authenticator content from unauthorized disclosure and modification.


### IA-5 (h)


Manage system authenticators by:
Requiring individuals to take, and having devices implement, specific controls to protect authenticators.


### IA-5 (i)


Manage system authenticators by:
Changing authenticators for group or role accounts when membership to those accounts changes.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

The registration process to receive all hardware/biometric (multifactor authenticators] should be conducted in person or by a trusted third party with authorization by a member of the approved registration authority (e.g., help desk or network administrator).




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)


- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Authenticators include passwords, cryptographic devices, biometrics, certificates, one-time password devices, and ID badges. Device authenticators include certificates and passwords. Initial authenticator content is the actual content of the authenticator (e.g., the initial password). In contrast, the requirements for authenticator content contain specific criteria or characteristics (e.g., minimum password length). Developers may deliver system components with factory default authentication credentials (i.e., passwords) to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant risk. The requirement to protect individual authenticators may be implemented via control PL-4 or PS-6 for authenticators in the possession of individuals and by controls AC-3, AC-6, and SC-28 for authenticators stored in organizational systems, including passwords stored in hashed or encrypted formats or files containing encrypted or hashed passwords accessible with administrator privileges.
Systems support authenticator management by organization-defined settings and restrictions for various authenticator characteristics (e.g., minimum password length, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication). Actions can be taken to safeguard individual authenticators, including maintaining possession of authenticators, not sharing authenticators with others, and immediately reporting lost, stolen, or compromised authenticators. Authenticator management includes issuing and revoking authenticators for temporary access when no longer needed.
