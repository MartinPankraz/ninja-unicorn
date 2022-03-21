---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part II Connecting the system on-premise
origurl: https://blogs.sap.com/2020/10/01/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-cloud-platform-scp-part-ii/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2020-10-01 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, XSUAA] # category should be a topic and sub-category primary product
tags: [sap-btp, cf, aad, security, principal-propagation, cloud-connector, sap-gateway, app-service, oauth]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---

## Extending the scenario

My initial blog post on this topic described the concepts and setup for principal propagation in a pure Cloud-based scenario for a Web application and its components (a frontend and backend unit) deployed on Microsoft Azure and SAP Business Technology Platform (BTP). With BTP being a powerful platform to extending existing mission critical SAP applications running on premises, a common requirement is to extend the reach for propagating the authenticated user (principal) beyond the Cloud boundaries. In those hybrid deployment models, the user’s data is still managed by corporate systems and exposed to the Cloud by specific protocol gateways and security components to ensure the highest level of control for this access.

In this part II of the blog series, you will learn how to extend the scenario of part I and implement end-to-end principal propagation from the initial login of the user in Azure Active Directory (Azure AD) all the way to BTP and the data access in an SAP system running on premise. The following requirements will be met
