---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# MA-4 - Nonlocal Maintenance
{: #ma-4}

## Control requirements
{: #control-requirements}



### MA-4 (a)


Approve and monitor nonlocal maintenance and diagnostic activities.


### MA-4 (b)


Allow the use of nonlocal maintenance and diagnostic tools only as consistent with organizational policy and documented in the security plan for the system.


### MA-4 (c)


Employ strong authentication in the establishment of nonlocal maintenance and diagnostic sessions.


### MA-4 (d)


Maintain records for nonlocal maintenance and diagnostic activities.


### MA-4 (e)


Terminate session and network connections when nonlocal maintenance is completed.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

Nonlocal maintenance and diagnostic activities are conducted by individuals who communicate through either an external or internal network. Local maintenance and diagnostic activities are carried out by individuals who are physically present at the system location and not communicating across a network connection. Authentication techniques used to establish nonlocal maintenance and diagnostic sessions reflect the network access requirements in IA-2. Strong authentication requires authenticators that are resistant to replay attacks and employ multi-factor authentication. Strong authenticators include PKI where certificates are stored on a token protected by a password, passphrase, or biometric. Enforcing requirements in MA-4 is accomplished, in part, by other controls. [SP 800-63B] provides additional guidance on strong authentication and authenticators.
