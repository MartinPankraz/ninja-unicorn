---
title: SAP on Azure - Load Balancing Web Application Servers for SAP BOBI using Azure Application Gateway
origurl: https://blogs.sap.com/2020/09/17/sap-on-azure-load-balancing-web-application-servers-for-sap-bobi-using-azure-application-gateway/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2020-09-17 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, AZURE_APPLICATION_GATEWAY] # category should be a topic and sub-category primary product
tags: [load-balancer, app-gateway, web-app-firewall, ssl-offload, sap-business-objects, sap-bobi]     # TAG names should always be lowercase

author:
  name: Dennis Padia
  link: https://people.sap.com/dennis.padia

comments: false

pin: false
---

In SAP BOBI multi-instance deployment, Web Application Servers (web tier) are running on two or more hosts. To distribute user load evenly across web servers, you need a load balancer to distribute traffic between end users and web servers. In Azure, you can either use Azure Load Balancer or Azure Application Gateway to manage traffic to your web application servers.
