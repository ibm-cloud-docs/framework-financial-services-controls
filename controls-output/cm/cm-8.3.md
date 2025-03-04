---
copyright:
  years: 2020, 2025

lastupdated: "2025-03-04"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# CM-8 (3) -  Automated Unauthorized Component Detection
{: #cm-8.3}

## Control requirements
{: #control-requirements}



### CM-8 (3) (a)


Detect the presence of unauthorized hardware, software, and firmware components within the system using _[IBM Assignment: automated mechanisms with a maximum five-minute delay in detection]_ _[IBM Assignment: continuously]_.


### CM-8 (3) (b)


Take the following actions when unauthorized components are detected: _[Selection (one or more): disable network access by such components; isolate the components; notify _[Assignment: organization-defined personnel or roles]_]_.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

Automated unauthorized component detection is applied in addition to the monitoring for unauthorized remote connections and mobile devices. Monitoring for unauthorized system components may be accomplished on an ongoing basis or by the periodic scanning of systems for that purpose. Automated mechanisms may also be used to prevent the connection of unauthorized components (see CM-7(9)). Automated mechanisms can be implemented in systems or in separate system components. When acquiring and implementing automated mechanisms, organizations consider whether such mechanisms depend on the ability of the system component to support an agent or supplicant in order to be detected since some types of components do not have or cannot support agents (e.g., IoT devices, sensors). Isolation can be achieved , for example, by placing unauthorized system components in separate domains or subnets or quarantining such components. This type of  component isolation is commonly referred to as “sandboxing.”
