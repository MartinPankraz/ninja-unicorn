---
title: SAP Migration to Azure - Performance Optimization Guidance
origurl: https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/sap-migration-to-azure-performance-optimization-guidance/ba-p/2112474
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-02-09 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [MIGRATION, AZURE_INFRASTRUCTURE] # category should be a topic and sub-category primary product
tags: [getting-started, performance, optimization, vm, storage, monitoring, migration, caching]     # TAG names should always be lowercase

author:
  name: Robert Biro
  link: https://people.sap.com/bobbiromsft

comments: false

pin: false
---

SAP NetWeaver migrations, whether they are between different datacenters/hosters or different OS/DB platforms are a known quantity in the SAP world. Many deeply experienced professionals are active in this field and have excellent understanding of the tools involved – DMO, R3load, migmon etc – as well as manual optimization techniques in order to get even the largest migrations done in least amount of downtime for their clients. What often however is not widely known are optimizations possible when migrating SAP NetWeaver systems to Azure to speed things up.
