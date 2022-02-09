---
title: BTP private linky swear with Azure – propagate your SAP principles via Private Link Service
origurl: https://blogs.sap.com/2021/10/28/btp-private-linky-swear-with-azure-propagate-your-sap-principels/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-10-28 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [principal-propagation, sap-btp, oauth, xsuaa, sap-gateway, azure-ad]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

Continuing with the implementation journey of BTP Private Link Service (PLS) we will have a closer look at the famous SAP Principal Propagation. The term describes the mapping of your BTP authenticated users to your SAP backend users to ensure audit trail and your complex server-side authorization mechanisms are applied. Your users on BTP or respectively CloudFoundry are identified by their email-address whereas SAP backend users usually have other ids.
