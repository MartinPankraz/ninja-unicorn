---
title: Extracting SAP data using OData - Part 4 - Handling large volumes of data
origurl: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/extracting-sap-data-using-odata-part-4-handling-large-volumes-of/ba-p/2849727
medium: blog #blog, github repos, linkedIn article, partner page
date: 2021-12-04 09:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, SYNAPSE] # category should be a topic and sub-category primary product
tags: [getting-started, odata, synapse, data-factory]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---

I hope you all enjoyed the summer with OData-based extraction and Synapse Pipelines. Time flies quickly, and we’re now in the fourth episode of this mini-blog series. You’ve learnt quite a lot! Initially, we built a simple pipeline with a single activity to copy data from the SAP system to data lake storage. But that solution evolved quickly, and now it supports storing metadata in an external store that decouples the management of OData services and pipelines. To extract data from a new service, you can just enter its name to the Azure Table Storage. You don’t have to make any changes in Synapse!
