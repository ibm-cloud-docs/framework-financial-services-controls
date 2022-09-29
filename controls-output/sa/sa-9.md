---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-29"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

               
# SA-9 - External Information System Services
{: #sa-9}

## Control requirements
{: #control-requirements}

The organization:

SA-9 (a)
    : Requires that providers of external information system services comply with organizational information security requirements and employ _[business continuity service level agreements]_ in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;

SA-9 (b)
    : Defines and documents government oversight and user roles and responsibilities with regard to external information system services; and

SA-9 (c)
    : Employs _[Continuous monitoring requirements must be met for external systems where customer information is processed or stored]_ to monitor security control compliance by external service providers on an ongoing basis.

## Additional IBM Cloud for Financial Services specifications
{: #additional-ibm-cloud-for-financial-services-specifications}

- Requirements for contingency planning and business continuity must be negotiated with third party service providers.
- Degradation of performance by the same external vendor to the organization across different regions should be documented.
- Authorized individuals include Federal Regulators in the event of insolvency.

## Implementation guidance
{: #implementation-guidance}

See the resources that follow to learn more about how to implement this control.

- [{{site.data.keyword.cloud_notm}} account setup](/docs/framework-financial-services?topic=framework-financial-services-shared-account-setup)

## IBM Cloud for Financial Services profile
{: #scc-fs-cloud-profile}

The goals that follow are part of the IBM Cloud for Financial Services v0.6.0 profile in [{{site.data.keyword.compliance_full}}](/docs/security-compliance?topic=security-compliance-getting-started).

| Requirement ID | Goals |
|----------------|-------|
| SA-9 (a) | - 3000045: Check whether the Financial Services Validated setting is enabled in account settings \n - 3000047: Check whether provisioned services are IAM enabled | 
{: caption="Goals for SA-9 in IBM Cloud for Financial Services v0.6.0 profile" caption-side="top"}

## NIST supplemental guidance
{: #nist-supplemental-guidance}

External information system services are services that are implemented outside of the authorization boundaries of organizational information systems. This includes services that are used by, but not a part of, organizational information systems. FISMA and OMB policy require that organizations using external service providers that are processing, storing, or transmitting federal information or operating information systems on behalf of the federal government ensure that such providers meet the same security requirements that federal agencies are required to meet. Organizations establish relationships with external service providers in a variety of ways including, for example, through joint ventures, business partnerships, contracts, interagency agreements, lines of business arrangements, licensing agreements, and supply chain exchanges. The responsibility for managing risks from the use of external information system services remains with authorizing officials. For services external to organizations, a chain of trust requires that organizations establish and retain a level of confidence that each participating provider in the potentially complex consumer-provider relationship provides adequate protection for the services rendered. The extent and nature of this chain of trust varies based on the relationships between organizations and the external providers. Organizations document the basis for trust relationships so the relationships can be monitored over time. External information system services documentation includes government, service providers, end user security roles and responsibilities, and service-level agreements. Service-level agreements define expectations of performance for security controls, describe measurable outcomes, and identify remedies and response requirements for identified instances of noncompliance.



