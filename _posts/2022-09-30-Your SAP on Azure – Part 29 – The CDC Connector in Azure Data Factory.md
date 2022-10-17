---
title: Extracting SAP data using the CDC connector
origurl: https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/extracting-sap-data-using-the-cdc-connector/ba-p/3644882
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-10-07 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, AZURE_DATA_FACTORY] # category should be a topic and sub-category primary product
tags: [cdc,getting-started,synapse]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: true
---
From time to time, there are updates to Azure services that excite me more than others. I’m interested mainly in application and data integration, so whenever new functionality is available, I want to test it and share it with you. Today I cover something BIG! If you have ever extracted data from an SAP system, you know it can quickly become a complex process. Transactional tables often contain millions or even billions of rows, and as the extraction process resource-intensive operation, the daily processing of the entire dataset is usually impossible. SAP Table connector, one of the most frequently used by SAP customers, heavily suffered from these challenges. Therefore I’m super excited that Azure Data Factory has a new family member. The new SAP CDC connector, released a couple of months ago and currently available in Public Preview, uses the SAP Operational Data Provisioning API to extract data. It’s an actual game changer – the new connector is robust, performant and reliable. And what I like the most, it also automatically merges all delta extracts into a consistent target data store.
