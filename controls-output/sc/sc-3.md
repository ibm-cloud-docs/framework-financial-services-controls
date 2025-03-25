---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-3 - Security Function Isolation
{: #sc-3}

## Control requirements
{: #control-requirements}



### SC-3 - 0


Isolate security functions from nonsecurity functions.









## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Ensuring isolation between {{site.data.keyword.satelliteshort}} management functions and workload functions](/docs/framework-financial-services?topic=framework-financial-services-satellite-architecture-connectivity-management-isolation)


- [Creating and connecting the management and workload VPCs](/docs/framework-financial-services?topic=framework-financial-services-vpc-architecture-connectivity-create-vpcs)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

Security functions are isolated from nonsecurity functions by means of an isolation boundary implemented within a system via partitions and domains. The isolation boundary controls access to and protects the integrity of the hardware, software, and firmware that perform system security functions. Systems implement code separation in many ways, such as through the provision of security kernels via processor rings or processor modes. For non-kernel code, security function isolation is often achieved through file system protections that protect the code on disk and address space protections that protect executing code. Systems can restrict access to security functions using access control mechanisms and by implementing least privilege capabilities. While the ideal is for all code within the defined security function isolation boundary to only contain security-relevant code, it is sometimes necessary to include nonsecurity functions as an exception. The isolation of security functions from nonsecurity functions can be achieved by applying the systems security engineering design principles in SA-8, including SA-8(1), SA-8(3), SA-8(4), SA-8(10), SA-8(12), SA-8(13), SA-8(14), and SA-8(18).
