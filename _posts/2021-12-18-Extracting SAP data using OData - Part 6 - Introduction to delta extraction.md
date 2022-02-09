---
title: Extracting SAP data using OData - Part 6 - Introduction to delta extraction
origurl: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/extracting-sap-data-using-odata-part-6-introduction-to-delta/ba-p/2860488
medium: blog #blog, github repos, linkedIn article, partner page
date: 2021-12-18 09:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, SYNAPSE] # category should be a topic and sub-category primary product
tags: [getting-started, odata, synapse, data-factory]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---

After five episodes of going through basic data extraction scenarios, we finally can deep dive into a more advanced topic. I already explained how crucial is extraction optimization. The created Synapse Pipeline can use client-side paging to chunk a large request into several smaller ones. In the last episode, we focused on data filtering to copy only the required information. Both solutions improve the performance and reliability of the extraction, but a full data copy is not always an answer. It is not uncommon to have millions or even billions of records in the largest tables. A daily extraction job to copy everything is pretty much impossible in such scenarios. It would take too much time and cause performance challenges on SAP application servers. Multiple extractions every day could cause even more problems.
