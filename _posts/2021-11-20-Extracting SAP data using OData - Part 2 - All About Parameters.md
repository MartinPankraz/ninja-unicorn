---
title: Extracting SAP data using OData - Part 2 - All About Parameters
origurl: https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/extracting-sap-data-using-odata-part-2-all-about-parameters/ba-p/2849518
medium: blog #blog, github repos, linkedIn article, partner page
date: 2021-11-20 09:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, SYNAPSE] # category should be a topic and sub-category primary product
tags: [getting-started,odata, synapse, data-factory]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---

OData services have become one the most powerful interfaces in SAP systems. In the last episode, we’ve built a simple pipeline that extracts business information from an OData service to a data lake and makes them available for further processing and analytics. We’ve created all required resources, including linked services and datasets, and we’ve used them to define the Copy Data activity. The extraction process run without any issues, and we were able to display data from the lake.
