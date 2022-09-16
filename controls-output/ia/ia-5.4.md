---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-16"
keywords: 
subcollection: controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 (4) - Automated Support For Password Strength Determination
{: #ia-5.4}

## Requirements
{: #requirements}

The organization employs automated tools to determine if password authenticators are sufficiently strong to satisfy [organization-defined requirements].

## NIST supplemental guidance
{: #supplemental-guidance}

This control enhancement focuses on the creation of strong passwords and the characteristics of such passwords (e.g., complexity) prior to use, the enforcement of which is carried out by organizational information systems in IA-5 (1).


## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- 3000001: Check whether IBMid password policy requires at least one uppercase letter
- 3000006: Check whether IBMid password may contain only printable ASCII characters (in the range 33 - 126)
- 3000007: Check whether IBMid password policy contains spaces or any of the following characters: \;:("?)<>
- 3000008: Check whether IBMid uses a password meter that coaches users to create strong passwords that exceed the minimum requirements
- 3000073: IBMid employs automated tools to determine if password authenticators satisfy IBMid password requirements
- 3000425: Check whether VPN for VPC authentication is configured with a strong pre-shared key with at least # characters
- 3000713: Check whether App ID password strength regex is configured
- 3000714: Check whether App ID advanced password policies are enabled
