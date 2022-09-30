---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-28"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# IA-5 (2) - Pki-Based Authentication
{: #ia-5.2}

## Control requirements
{: #control-requirements}

The information system, for PKI-based authentication:

IA-5 (2) (a)
    : Validates certifications by constructing and verifying a certification path to an accepted trust anchor including checking certificate status information;

IA-5 (2) (b)
    : Enforces authorized access to the corresponding private key;

IA-5 (2) (c)
    : Maps the authenticated identity to the account of the individual or group; and

IA-5 (2) (d)
    : Implements a local cache of revocation data to support path discovery and validation in case of inability to access revocation information via the network.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- TLS certificate revocation status checking, and revocation status caching is only applicable to connections between a browser and server.

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Status information for certification paths includes, for example, certificate revocation lists or certificate status protocol responses. For PIV cards, validation of certifications involves the construction and verification of a certification path to the Common Policy Root trust anchor including certificate policy processing.



