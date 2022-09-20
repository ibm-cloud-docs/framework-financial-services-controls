---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-20"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SI-8 - Spam Protection
{: #si-8}

## Requirements
{: #requirements}

The organization:

- \[a.\] Employs spam protection mechanisms at information system entry and exit points to detect and take action on unsolicited messages; and

- \[b.\] Updates spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

The organization must send email to or on behalf of the customer, in accordance with customer requirements including the following:
- Email must be sent in accordance  with Domain-based Message Authentication, Reporting &amp; Conformance (DMARC) to protect their domain from unauthorized use (i.e., email spoofing).
- Organization senders using customer domains, must use a subdomain in the message From header, as opposed to a top level domain.
- Organizations must provide customers with the needed information (including any changes) for customers to publish Domain Keys Identified Mail (DKIM) and Sender Policy Framework (SPF) records for the assigned subdomain.
- DKIM key must be 1024 bits in length.

## NIST supplemental guidance
{: #supplemental-guidance}

Information system entry and exit points include, for example, firewalls, electronic mail servers, web servers, proxy servers, remote-access servers, workstations, mobile devices, and notebook/laptop computers. Spam can be transported by different means including, for example, electronic mail, electronic mail attachments, and web accesses. Spam protection mechanisms include, for example, signature definitions.

