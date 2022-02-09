---
title: Hands-On Lab - Implementing a Node.JS client as Azure Bot and leveraging principal propagation between Azure and SAP Netweaver OData services
origurl: https://github.com/ROBROICH/Teams-Chatbot-SAP-NW-Principal-Propagation
medium: github repos #blog, github repos, linkedIn article, partner pages
date: 2020-08-24 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, TEAMS] # category should be a topic and sub-category primary product
tags: [teams, aad, chatbot, sap-es5, principal-propagation]     # TAG names should always be lowercase

author:
  name: Roman Broich
  link: https://www.linkedin.com/in/roman-broich/

comments: false

pin: false
---

This hands-on lab demonstrates the implementation of a principal propagation, also known as OAuth2 SAML Bearer Assertion Flow, between Azure AD and SAP Netweaver(NW) OData-services. The scenario of this lab is a basic Node.JS client to display data from SAP NW OData services in Microsoft Teams using an Azure Bot.

In a nutshell: This scenario enables Azure developers to implement cloud-native Azure applications that are enabled to consume OData data-sources from SAP Netweaver. This includes applying and mapping the SAP ABAP authorizations of the same user-logged on to Azure AD and maintained in SAP NW.

As a result, this approach allows to reuse existing SAP NW security, authorization- and role-concepts within Azure based applications like the Azure Bot demonstrated in this example.
