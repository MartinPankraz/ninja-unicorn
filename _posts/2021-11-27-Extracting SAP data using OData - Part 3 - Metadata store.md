---
title: Extracting SAP data using OData - Part 3 - Metadata store
origurl: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/extracting-sap-data-using-odata-part-3-metadata-store/ba-p/2849544
medium: blog #blog, github repos, linkedIn article, partner page
date: 2021-11-27 09:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, SYNAPSE] # category should be a topic and sub-category primary product
tags: [getting-started, odata, synapse, data-factory]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---

Welcome to the third episode of this mini blog series, where I show you how to deal with OData extraction from the SAP system using Synapse Pipelines. In the first episode, we’ve built a simple pipeline that extracts data from a selected OData service and saves it to the data lake. Then, a week later, we enhanced the design to support parameters, which eliminated some of the hardcoded values. It allows us to change the OData service we want to use without modifying the pipeline or resources.
