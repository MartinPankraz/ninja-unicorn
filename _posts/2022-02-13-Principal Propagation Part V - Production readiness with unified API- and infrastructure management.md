---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part V - Production readiness with unified API- and infrastructure management
origurl: https://blogs.sap.com/2022/02/13/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-business-technology-platform-btp-part-v-production-readiness-with-unified-api-and-infrastructure-management/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-02-13 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, APIM] # category should be a topic and sub-category primary product
tags: [apim, sap-btp, cf, aad, security, principal-propagation, cloud-connector, sap-gateway, app-service, power-virtual-agent, onpremises-data-gateway, teams, oauth]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---

# API Management and Monitoring

In part II of this blog series, the scenario has been extended with an OData service exposed by the SAP backend system in the corporate network. The service endpoint was never directly accessed from the cloud. Parts II and III demonstrated a setup using SAP Cloud Connector (SCC) to propagate the authenticated user (“principal”) from SAP BTP, part IV proposed an alternative solution with the Microsoft On-Premises Data Gateway (OPDG) connected to Microsoft Power Platform. SCC and OPDG are both security-critical components deployed in the corporate network and share a set of common features to secure the access to the on-premise product catalogue data in the scenario:
