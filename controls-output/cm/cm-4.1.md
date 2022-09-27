---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-27"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# CM-4 (1) - Separate Test Environments
{: #cm-4.1}

## Control requirements
{: #control-requirements}

The organization analyzes changes to the information system in a separate test environment before implementation in an operational environment, looking for security impacts due to flaws, weaknesses, incompatibility, or intentional malice.

## Additional IBM Cloud for Financial Services specifications
{: #additional-fs-cloud-specifications}

- The test environment must mirror the production environment.  
- Customer data must not be placed into non-production environments.

## NIST supplemental guidance
{: #nist-supplemental-guidance}

Separate test environment in this context means an environment that is physically or logically isolated and distinct from the operational environment. The separation is sufficient to ensure that activities in the test environment do not impact activities in the operational environment, and information in the operational environment is not inadvertently transmitted to the test environment. Separate environments can be achieved by physical or logical means. If physically separate test environments are not used, organizations determine the strength of mechanism required when implementing logical separation (e.g., separation achieved through virtual machines).



