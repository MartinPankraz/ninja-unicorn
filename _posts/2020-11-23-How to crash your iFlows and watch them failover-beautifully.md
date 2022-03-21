---
title: How to crash your iflows and watch them failover beautifully
origurl: https://blogs.sap.com/2020/11/23/how-to-crash-your-iflows-and-watch-them-failover-beautifully/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2020-11-23 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DISASTER_RECOVERY, FRONT_DOOR] # category should be a topic and sub-category primary product
tags: [cpi, integration-suite, multi-tenant, apim, cloud-connector, s4, failover, sap-btp]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

Are you happy with redundant deployments in availability zones in a single cloud region? Are your iFlows down regularly due to CPI maintenance windows? Or are you striving for cross-region failovers? SAP deploys their CloudFoundry services for its multi-cloud environment (Azure, AWS, GCP and Alibaba) zone-redundantly. You can find the reference here.
