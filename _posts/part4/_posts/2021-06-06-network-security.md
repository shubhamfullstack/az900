---
layout: post
title:  "Network Security"
tag: Part 4
---

# Network Security

1. The objective of defense in depth is to protect information and prevent it from being stolen by those who aren't authorized to access it.

2. A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules. You can create firewall rules that specify ranges of IP addresses. Only clients granted IP addresses from within those ranges are allowed to access the destination server. Firewall rules can also include specific network protocol and port information.

### Azure Firewall

1. Azure Firewall is a managed, cloud-based network security service that helps protect resources in your Azure virtual networks. A virtual network is similar to a traditional network that you'd operate in your own datacenter. 

2. Azure Firewall is a stateful firewall. A stateful firewall analyzes the complete context of a network connection, not just an individual packet of network traffic. 

3. Azure Application Gateway also provides a firewall that's called the web application firewall (WAF). WAF provides centralized, inbound protection for your web applications against common exploits and vulnerabilities. Azure Front Door and Azure Content Delivery Network also provide WAF services.

### DDoS

1. A distributed denial of service attack attempts to overwhelm and exhaust an application's resources, making the application slow or unresponsive to legitimate users. 

2. Azure DDoS Protection (Standard) helps protect your Azure resources from DDoS attacks.

### network security groups

1. A network security group enables you to filter network traffic to and from Azure resources within an Azure virtual network.
