---
copyright:
  years: 2020, 2022
lastupdated: "2022-09-01"
keywords: 
subcollection: controls
---


{{site.data.keyword.attribute-definition-list}}


# SC-7(8) - Route Traffic To Authenticated Proxy Servers
{: #sc-7.8}

## Requirements
{: #requirements}

The information system routes [organization-defined internal communications traffic] to [organization-defined external networks] through authenticated proxy servers at managed interfaces.

## Control Supplemental Guidance
{: #supplemental-guidance}

External networks are networks outside of organizational control. A proxy server is a server (i.e., information system or application) that acts as an intermediary for clients requesting information system resources (e.g., files, connections, web pages, or services) from other organizational servers. Client requests established through an initial connection to the proxy server are evaluated to manage complexity and to provide additional protection by limiting direct connectivity. Web content filtering devices are one of the most common proxy servers providing access to the Internet. Proxy servers support logging individual Transmission Control Protocol (TCP) sessions and blocking specific Uniform Resource Locators (URLs), domain names, and Internet Protocol (IP) addresses. Web proxies can be configured with organization-defined lists of authorized and unauthorized websites.

| Parameter ID | Values | Label or Choices |
|---|---|---|
| sc-7.8_prm_1 |  | organization-defined internal communications traffic |
| sc-7.8_prm_2 |  | organization-defined external networks |