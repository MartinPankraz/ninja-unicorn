---
title: SAP private linky swear with Azure – to WAF or not to WAF🐶 with SAP Private Link
origurl: https://blogs.sap.com/2022/11/30/sap-private-linky-swear-with-azure-to-waf-or-not-to-waf%f0%9f%90%b6-with-sap-private-link/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-11-30 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [sap-btp,app-gateway,sap-pls,key-vault,certificate,automation]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Dear community,

Continuing with the implementation journey of [SAP Private Link Service](https://help.sap.com/docs/PRIVATE_LINK/42acd88cb4134ba2a7d3e0e62c9fe6cf/af86a457ffd84324a6691c6ea1649dd6.html) (PLS) for Azure we will have a closer look at connecting [privately](https://learn.microsoft.com/azure/application-gateway/private-link) to your Azure workloads via the [Azure Application Gateway](https://learn.microsoft.com/azure/application-gateway/overview) (App Gateway) using the Microsoft backbone. Why is this interesting?
