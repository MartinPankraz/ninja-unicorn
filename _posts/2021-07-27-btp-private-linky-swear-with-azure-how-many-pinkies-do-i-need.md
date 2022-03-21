---
title: BTP private linky swear with Azure – how many pinkies do I need? Architecture impact of Private Link Service.
origurl: https://blogs.sap.com/2021/07/27/btp-private-linky-swear-with-azure-how-many-pinkies-do-i-need/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-07-27 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [hub-spoke, architecture, private-link, sap-btp, cloud-connector]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

Continuing with the implementation journey of BTP private Link we eventually need to reflect on our actual SAP system landscape outside of BTP. Are you running three SAP backend stages (dev, qa and prod), or are you one of those brave cloud folks having only prod and non-prod? Are they isolated in different network subnets or regions on Azure? Against which system stage do you develop from BTP? Are your workloads grouped by Subaccounts or by spaces within Cloud Foundry?
