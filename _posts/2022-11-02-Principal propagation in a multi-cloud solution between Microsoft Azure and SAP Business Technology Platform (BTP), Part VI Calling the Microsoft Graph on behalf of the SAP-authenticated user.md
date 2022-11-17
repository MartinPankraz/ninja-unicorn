---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part VI Calling the Microsoft Graph on behalf of the SAP-authenticated user
origurl: https://blogs.sap.com/2022/11/02/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-business-technology-platform-btp-part-vi-calling-the-microsoft-graph-on-behalf-of-the-sap-authenticated-user/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-11-02 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, MICROSOFT_GRAPH] # category should be a topic and sub-category primary product
tags: [sap-btp,xsuaa,aad,sap-ias,security,oidc,oauth,destination,microsoft-graph,principal-propagation,cloud-connector]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---
Microsoft Graph
In the previous parts of this blog series, data has always been retrieved from an SAP-provided service. [Part I](https://blogs.sap.com/2020/07/17/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-cloud-platform-scp/) started the journey with a simple Web Service implemented as a [Java servlet](https://github.com/raepple/azure-scp-principal-propagation/blob/master/SCP/service/application/src/main/java/com/contoso/sample/HelloWorldServlet.java) deployed on the SAP Business Technology Platform (BTP) [Cloud Foundry](https://help.sap.com/viewer/3504ec5ef16548778610c7e89cc0eac3/Cloud/en-US/9c7092c7b7ae4d49bc8ae35fdd0e0b18.html) (CF) environment. From [part II](https://blogs.sap.com/2020/10/01/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-cloud-platform-scp-part-ii/) onwards, the service is hosted on an SAP Gateway system. With this part, we are turning the data and token exchange flow for propagating the authenticated user (principal) into the opposite direction: The user logs on to a web application on BTP which accesses data on behalf of this user from Microsoft Cloud service resources.
