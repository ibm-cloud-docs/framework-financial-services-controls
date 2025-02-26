---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# AC-6 (5) -  Privileged Accounts
{: #ac-6 (5)}

## Control requirements
{: #control-requirements}



### AC-6 (5) - 0


Restrict privileged accounts on the system to _[Assignment: organization-defined personnel or roles]_.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Container Security Requirements:
• Containers must not run as ‘privileged’ or ‘root’ (includes running with root privileges). In situations where these requirements can’t be met, the teams should follow the security exception process.







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Privileged accounts, including super user accounts, are typically described as system administrator for various types of commercial off-the-shelf operating systems. Restricting privileged accounts to specific personnel or roles prevents day-to-day users from accessing privileged information or privileged functions. Organizations may differentiate in the application of restricting privileged accounts between allowed privileges for local accounts and for domain accounts provided that they retain the ability to control system configurations for key parameters and as otherwise necessary to sufficiently mitigate risk.
