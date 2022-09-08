---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-08"
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


## IBM Cloud for Financial Services Profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.5.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

- [3000471: Check that at least # Virtual Private Cloud(VPC)s have been created](https://cloud.ibm.com/security-compliance/goals/3000471?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
- [3000472: Check that at least # instances of Transit Gateway have been created](https://cloud.ibm.com/security-compliance/goals/3000472?page=profile&profile_id=2799&profile_type=1&profile_name=IBM%20Cloud%20for%20Financial%20Services%20v0.5.0){: external}
