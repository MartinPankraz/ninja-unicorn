---
title: Your SAP on Azure – Part 10 – B2B Integration
origurl: https://blogs.sap.com/2018/10/09/your-sap-on-azure-part-10-b2b-integration/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-10-09 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
Using Azure Logic Apps as the integration service is a smart way to connect your organization with the external trading partners. You don’t have to buy hardware or software licenses so there are no upfront costs. It’s not important how many messages you send or how much data is transmitted – all applications are highly scalable, and you pay only for what you have used. In the last post, I showed that building a workflow is also easy. We have designed two applications that communicate with an SAP system and today we are going to enhance the solution by establishing a cross-company integration. I will go through all required steps to enable a secure communication channel using the AS2 protocol to send encrypted and signed messages using certificates. On top, we will validate IDocs against a schema and modify them using XML transformation. Azure Data lake will be the storage for our messages archive and Key Vault will protect private keys. As always, plenty of knowledge in one post!
