---
title: SAP private linky swear with Azure – global scale with Azure Cosmos DB and SAP Private Link
origurl: https://blogs.sap.com/2023/01/27/sap-private-linky-swear-with-azure-global-scale-with-azure-cosmos-db-with-sap-private-link/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-01-27 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [sap-btp, app-gateway, sap-pls, cosmos-db, geo-replication]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Continuing with the implementation journey of [SAP Private Link Service](https://help.sap.com/docs/PRIVATE_LINK/42acd88cb4134ba2a7d3e0e62c9fe6cf/af86a457ffd84324a6691c6ea1649dd6.html) (PLS) for Azure we will have a closer look at connecting [privately](https://learn.microsoft.com/azure/application-gateway/private-link) to the fully managed [Azure Cosmos DB](https://learn.microsoft.com/azure/cosmos-db/introduction) (Cosmos DB) using the Microsoft backbone.
