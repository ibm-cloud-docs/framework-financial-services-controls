---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SC-3 - Security Function Isolation
{: #sc-3}

## Requirements
{: #requirements}

The information system isolates security functions from nonsecurity functions.

## Control Supplemental Guidance
{: #supplemental-guidance}

The information system isolates security functions from nonsecurity functions by means of an isolation boundary (implemented via partitions and domains). Such isolation controls access to and protects the integrity of the hardware, software, and firmware that perform those security functions. Information systems implement code separation (i.e., separation of security functions from nonsecurity functions) in a number of ways, including, for example, through the provision of security kernels via processor rings or processor modes. For non-kernel code, security function isolation is often achieved through file system protections that serve to protect the code on disk, and address space protections that protect executing code. Information systems restrict access to security functions through the use of access control mechanisms and by implementing least privilege capabilities. While the ideal is for all of the code within the security function isolation boundary to only contain security-relevant code, it is sometimes necessary to include nonsecurity functions within the isolation boundary as an exception.
