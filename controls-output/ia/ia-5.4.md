---

copyright:
  years: 2020, 2023

lastupdated: "2023-03-08"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# IA-5 (4) - Automated Support for Password Strength Determination
{: #ia-5.4}

## Control requirements
{: #control-requirements}

IA-5 (4) - 0
    : The organization employs automated tools to determine if password authenticators are sufficiently strong to satisfy [Assignment: organization-defined requirements].

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The rules related to this control that follow are part of the IBM Cloud for Financial Services v1.1.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- Check whether App ID advanced password policies are enabled 
- IBMid employs automated tools to determine if password authenticators satisfy IBMid password requirements 
- Check whether IBMid password may contain only printable ASCII characters (in the range 33 - 126) 
- Check whether App ID password strength regex is configured 
- Check whether IBMid password policy policy contains spaces or any of the following characters: ;:("?)<> 
- Check whether VPN for VPC authentication is configured with a strong pre-shared key with at least # characters 
- Check whether IBMid password policy requires at least one uppercase letter 
- Check whether IBMid uses a password meter that coaches users to create strong passwords that exceed the minimum requirements

## NIST supplemental guidance
{: #nist-supplemental-guidance}

This control enhancement focuses on the creation of strong passwords and the characteristics of such passwords (e.g., complexity) prior to use, the enforcement of which is carried out by organizational information systems in IA-5 (1).





