---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# IA-5 (2) -  Public Key-based Authentication
{: #ia-5.2}

## Control requirements
{: #control-requirements}



### IA-5 (2) (a)


For public key-based authentication:
(1) Enforce authorized access to the corresponding private key; and
(2) Map the authenticated identity to the account of the individual or group.


### IA-5 (2) (b)


When public key infrastructure (PKI) is used:
(1) Validate certificates by constructing and verifying a certification path to an accepted trust anchor, including checking certificate status information; and
(2) Implement a local cache of revocation data to support path discovery and validation.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

TLS certificate revocation status checking, and revocation status caching is only applicable to connections between a browser and server.







## NIST supplemental guidance
{: #nist-supplemental-guidance}

Public key cryptography is a valid authentication mechanism for individuals, machines, and devices. For PKI solutions, status information for certification paths includes certificate revocation lists or certificate status protocol responses. For PIV cards, certificate validation involves the construction and verification of a certification path to the Common Policy Root trust anchor, which includes certificate policy processing. Implementing a local cache of revocation data to support path discovery and validation also supports system availability in situations where organizations are unable to access revocation information via the network.
