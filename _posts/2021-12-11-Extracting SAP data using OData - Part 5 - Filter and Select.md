---
title: Extracting SAP data using OData - Part 5 - Filter and Select
origurl: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/extracting-sap-data-using-odata-part-5-filter-and-select/ba-p/2849814
medium: blog #blog, github repos, linkedIn article, partner page
date: 2021-12-11 09:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, SYNAPSE] # category should be a topic and sub-category primary product
tags: [getting-started, odata, synapse, data-factory]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---

Over the last five episodes, we’ve built quite a complex Synapse Pipeline that allows extracting SAP data using OData protocol. Starting from a single activity in the pipeline, the solution grew, and it now allows to process multiple services on a single execution. We’ve implemented client-side caching to optimize the extraction runtime and eliminate short dumps at SAP. But that’s definitely not the end of the journey!
