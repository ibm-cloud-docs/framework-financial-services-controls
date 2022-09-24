---

copyright:
  years: 2020, 2022

lastupdated: "2022-09-24"

keywords: 
subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

         
# MP-5 - Media Transport
{: #mp-5}

## Requirements
{: #requirements}

The organization:

- (a) Protects and controls _[all media with sensitive information] during transport outside of controlled areas using [for digital media, encryption using a FIPS 140-2 validated encryption module; for non-digital media, secured in locked container]_;
- (b) Maintains accountability for information system media during transport outside of controlled areas;
- (c) Documents activities associated with the transport of information system media; and
- (d) Restricts the activities associated with the transport of information system media to authorized personnel.

## NIST supplemental guidance
{: #supplemental-guidance}

Information system media includes both digital and non-digital media. Digital media includes, for example, diskettes, magnetic tapes, external/removable hard disk drives, flash drives, compact disks, and digital video disks. Non-digital media includes, for example, paper and microfilm. This control also applies to mobile devices with information storage capability (e.g., smart phones, tablets, E-readers), that are transported outside of controlled areas. Controlled areas are areas or spaces for which organizations provide sufficient physical and/or procedural safeguards to meet the requirements established for protecting information and/or information systems. Physical and technical safeguards for media are commensurate with the security category or classification of the information residing on the media. Safeguards to protect media during transport include, for example, locked containers and cryptography. Cryptographic mechanisms can provide confidentiality and integrity protections depending upon the mechanisms used. Activities associated with transport include the actual transport as well as those activities such as releasing media for transport and ensuring that media enters the appropriate transport processes. For the actual transport, authorized transport and courier personnel may include individuals from outside the organization (e.g., U.S. Postal Service or a commercial transport or delivery service). Maintaining accountability of media during transport includes, for example, restricting transport activities to authorized personnel, and tracking and/or obtaining explicit records of transport activities as the media moves through the transportation system to prevent and detect loss, destruction, or tampering. Organizations establish documentation requirements for activities associated with the transport of information system media in accordance with organizational assessments of risk to include the flexibility to define different record-keeping methods for the different types of media transport as part of an overall system of transport-related records.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| mp-5_prm_1 | all media with sensitive information | organization-defined types of information system media |
| mp-5_prm_2 | for digital media, encryption using a FIPS 140-2 validated encryption module; for non-digital media, secured in locked container | organization-defined security safeguards |

