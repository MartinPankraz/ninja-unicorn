---
title: SAP Principal Propagation without Secrets - How Managed Identity in APIM Simplifies Everything
origurl: https://community.sap.com/t5/technology-blog-posts-by-members/sap-principal-propagation-without-secrets-how-managed-identity-in-apim/ba-p/14091769
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2025-05-02 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, SAP] # category should be a topic and sub-category primary product
tags: [entra-id,managed-identity,security,s4,certificate,passwordless]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://community.sap.com/t5/user/viewprofilepage/user-id/143781

comments: false

pin: false
---
SAP Principal Propagation (for simplicity often also referred to as SSO) is the gold standard for app integration – especially when it comes to 3rd party apps such as Microsoft Power Platform. Building on top of my prior blog on API Management usage for SAP SSO, I am sharing today how you can fully eliminate the passwords or certificates for the token exchange previously required.
