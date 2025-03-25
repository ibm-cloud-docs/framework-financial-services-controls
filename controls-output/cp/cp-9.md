---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-26"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CP-9 - System Backup
{: #cp-9}

## Control requirements
{: #control-requirements}



### CP-9 (a)


Conduct backups of user-level information contained in _[Assignment: organization-defined system components]_ _[IBM Assignment: daily incremental; weekly full]_.


### CP-9 (b)


Conduct backups of system-level information contained in the system _[IBM Assignment: daily incremental; weekly full]_.


### CP-9 (c)


Conduct backups of system documentation, including security- and privacy-related documentation _[IBM Assignment: daily incremental; weekly full]_.


### CP-9 (d)


Protect the confidentiality, integrity, and availability of backup information.






## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

Container Security Requirements: 
• Backup of following cluster objects must be done to allow recovery in case of major disruption: CP-9 Information System Backup
 a. Namespace
 b. deployments 
 c. configurations maps
 d. secrets 
 e. daemon sets
 f. services 
g. persistent volumes 
• Cluster configuration data and metadata must be backed up every 4 hours; the last 4 iterations of the backup must be kept for DR and forensics purposes.
• Container registry components must be backed up including configurations. Images must be backed up as well and kept for at least 7 days in case of forensics request.




## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.


- [Business continuity and disaster recovery overview](/docs/framework-financial-services?topic=framework-financial-services-shared-bcdr)






## NIST supplemental guidance
{: #nist-supplemental-guidance}

System-level information includes system state information, operating system software, middleware, application software, and licenses. User-level information includes information other than system-level information. Mechanisms employed to protect the integrity of system backups include digital signatures and cryptographic hashes. Protection of system backup information while in transit is addressed by MP-5 and SC-8. System backups reflect the requirements in contingency plans as well as other organizational requirements for backing up information. Organizations may be subject to laws, executive orders, directives, regulations, or policies with requirements regarding specific categories of information (e.g., personal health information). Organizational personnel consult with the senior agency official for privacy and legal counsel regarding such requirements.
