---
title: BTP private linky swear with Azure – keep the auditor happy with Private Link Service
origurl: https://blogs.sap.com/2021/11/19/btp-private-linky-swear-with-azure-keep-the-auditor-happy/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-11-19 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [sap-web-dispatcher, sap-btp, security, rfc]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

Continuing with the implementation journey of BTP Private Link Service (PLS) we will have a closer look at limiting exposure of your http endpoints and RFCs. Your ERP is shipped with roughly 40k RFCs that can be remote enabled and a similar magnitude for http endpoints. Rumour has it you won’t be using all of them 😉
