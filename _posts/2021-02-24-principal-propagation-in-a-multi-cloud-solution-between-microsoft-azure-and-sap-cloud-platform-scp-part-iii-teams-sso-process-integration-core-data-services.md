---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part III Teams SSO, Process Integration & Core Data Services
origurl: https://blogs.sap.com/2021/02/24/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-cloud-platform-scp-part-iii-teams-sso-process-integration-core-data-services/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-02-24 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, XSUAA] # category should be a topic and sub-category primary product
tags: [sap-btp, cf, aad, security, principal-propagation, cloud-connector, sap-gateway, app-service, chatbot, teams, cpi, oauth]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---

## Finalizing the scenario

Up to this point in the blog series, you have a working setup to enable end-to-end principal propagation between Azure, SAP Business Technology Platform (BTP) and an SAP ABAP system on premise. However, we are still missing a real application scenario on top of the infrastructure. Testing so far occurred at the raw HTTP(S) protocol level using Postman as our tool of choice. With this 3rd part of the blog series, you will build a distributed cloud application with different components running in Azure, BTP and SAP backend on-premise. From an end-user perspective, this application offers a chat bot interface in Microsoft Teams, which allows to search for IT equipment in a product catalogue. The product data such as price, category and an image is retrieved from the SAP backend system, where access control is enforced based on the Azure AD-authenticated user’s authorizations. Let’s have a look at the application components in more detail.
