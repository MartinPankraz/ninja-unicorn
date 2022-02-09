---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part I Building the foundation
origurl: https://blogs.sap.com/2020/07/17/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-cloud-platform-scp/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2020-07-17 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, XSUAA] # category should be a topic and sub-category primary product
tags: [sap-btp, cf, aad, security, principal-propagation, oauth]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---

## Scenario Overview

Modern business applications running in the Cloud typically consist of many independent (micro)services. This architectural style enables them to rapidly respond to market conditions. However, such highly distributed systems also come with costs, e.g. for their increased communication overhead and additional operational complexity. Quite often, those services are not deployed in a single system landscape. They are distributed across different regions, geographies (e.g. for availability and performance reasons), or even clouds. In such a multi-cloud setup with multiple platforms from different vendors, interoperability and standards become an important aspect to consider when designing a solution. This is especially true for the security of the solution from an end-to-end perspective.
