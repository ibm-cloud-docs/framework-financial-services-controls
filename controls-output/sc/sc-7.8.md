---
copyright:
  years: 2020, 2025

lastupdated: "2025-02-27"

keywords:

subcollection: framework-financial-services-controls
---

{{site.data.keyword.attribute-definition-list}}

# SC-7 (8) -  Route Traffic to Authenticated Proxy Servers
{: #sc-7.8}

## Control requirements
{: #control-requirements}



### SC-7 (8) - 0


Route _[Assignment: organization-defined internal communications traffic]_ to _[Assignment: organization-defined external networks]_ through authenticated proxy servers at managed interfaces.












## NIST supplemental guidance
{: #nist-supplemental-guidance}

External networks are networks outside of organizational control. A proxy server is a server (i.e., system or application) that acts as an intermediary for clients requesting system resources from non-organizational or other organizational servers. System resources that may be requested include files, connections, web pages, or services. Client requests established through a connection to a proxy server are assessed to manage complexity and provide additional protection by limiting direct connectivity. Web content filtering devices are one of the most common proxy servers that provide access to the Internet. Proxy servers can support the logging of Transmission Control Protocol sessions and the blocking of specific Uniform Resource Locators, Internet Protocol addresses, and domain names. Web proxies can be configured with organization-defined lists of authorized and unauthorized websites. Note that proxy servers may inhibit the use of virtual private networks (VPNs) and create the potential for “man-in-the-middle” attacks (depending on the implementation).
