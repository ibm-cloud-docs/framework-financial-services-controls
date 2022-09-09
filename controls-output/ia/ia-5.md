---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-09"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 - Authenticator Management
{: #ia-5}

## Requirements
{: #requirements}

The organization manages information system authenticators by:

- \[a.\] Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, or device receiving the authenticator;

- \[b.\] Establishing initial authenticator content for authenticators defined by the organization;

- \[c.\] Ensuring that authenticators have sufficient strength of mechanism for their intended use;

- \[d.\] Establishing and implementing administrative procedures for initial authenticator distribution, for lost/compromised or damaged authenticators, and for revoking authenticators;

- \[e.\] Changing default content of authenticators prior to information system installation;

- \[f.\] Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators;

- \[g.\] Changing/refreshing authenticators [90 days for user passwords and 365 days for system-to-system authenticators];

- \[h.\] Protecting authenticator content from unauthorized disclosure and modification;

- \[i.\] Requiring individuals to take, and having devices implement, specific security safeguards to protect authenticators; and

- \[j.\] Changing authenticators for group/role accounts when membership to those accounts changes.

## Control Supplemental Guidance
{: #supplemental-guidance}

Individual authenticators include, for example, passwords, tokens, biometrics, PKI certificates, and key cards. Initial authenticator content is the actual content (e.g., the initial password) as opposed to requirements about authenticator content (e.g., minimum password length). In many cases, developers ship information system components with factory default authentication credentials to allow for initial installation and configuration. Default authentication credentials are often well known, easily discoverable, and present a significant security risk. The requirement to protect individual authenticators may be implemented via control PL-4 or PS-6 for authenticators in the possession of individuals and by controls AC-3, AC-6, and SC-28 for authenticators stored within organizational information systems (e.g., passwords stored in hashed or encrypted formats, files containing encrypted or hashed passwords accessible with administrator privileges). Information systems support individual authenticator management by organization-defined settings and restrictions for various authenticator characteristics including, for example, minimum password length, password composition, validation time window for time synchronous one-time tokens, and number of allowed rejections during the verification stage of biometric authentication. Specific actions that can be taken to safeguard authenticators include, for example, maintaining possession of individual authenticators, not loaning or sharing individual authenticators with others, and reporting lost, stolen, or compromised authenticators immediately. Authenticator management includes issuing and revoking, when no longer needed, authenticators for temporary access such as that required for remote maintenance. Device authenticators include, for example, certificates and passwords.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| ia-5_prm_1 | 90 days for user passwords and 365 days for system-to-system authenticators | organization-defined time period by authenticator type |


## Related Resources
{: #related_resources}

See the resources that follow to learn more about how to implement this control.

- [Handling and securing secrets](/docs/framework-financial-services?topic=framework-financial-services-shared-secrets)
- [Consumer accounts for application provider workloads](/docs/framework-financial-services?topic=framework-financial-services-shared-account-consumer)

## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

### Part b
{: #scc-fs-cloud-profile-b}

- [3000075: IBM Cloud IAM establishes initial authenticator content for authenticators that are defined by the organization (for example, API keys)](https://cloud.ibm.com/security-compliance/goals/3000075?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part c
{: #scc-fs-cloud-profile-c}

- [3000065: IBMid ensures that passwords have sufficient strength for their intended use](https://cloud.ibm.com/security-compliance/goals/3000065?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000066: IBM Cloud IAM ensures that authenticators, such as API keys, have sufficient strength for their intended use](https://cloud.ibm.com/security-compliance/goals/3000066?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000425: Check whether VPN for VPC authentication is configured with a strong pre-shared key with at least # characters](https://cloud.ibm.com/security-compliance/goals/3000425?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000713: Check whether App ID password strength regex is configured](https://cloud.ibm.com/security-compliance/goals/3000713?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000714: Check whether App ID advanced password policies are enabled](https://cloud.ibm.com/security-compliance/goals/3000714?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000720: Check whether App ID prevent username in password policy is enabled](https://cloud.ibm.com/security-compliance/goals/3000720?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000903: Check whether OpenShift cluster has image pull secrets enabled](https://cloud.ibm.com/security-compliance/goals/3000903?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part f
{: #scc-fs-cloud-profile-f}

- [3000067: IBMid establishes minimum and maximum lifetime restrictions and reuse conditions for authenticators](https://cloud.ibm.com/security-compliance/goals/3000067?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000068: IBM Cloud IAM establishes minimum and maximum lifetime restrictions and reuse conditions for authenticators, such as API keys](https://cloud.ibm.com/security-compliance/goals/3000068?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000718: Check whether App ID minimum period between password changes policy is set to greater than 0](https://cloud.ibm.com/security-compliance/goals/3000718?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}

### Part g
{: #scc-fs-cloud-profile-g}

- [3000024: Check whether IBM Cloud API keys that are managed in IAM are rotated at least every # days](https://cloud.ibm.com/security-compliance/goals/3000024?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000235: Check whether Hyper Protect Crypto Services encryption keys that are generated by the service are rotated automatically at least every # months](https://cloud.ibm.com/security-compliance/goals/3000235?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
