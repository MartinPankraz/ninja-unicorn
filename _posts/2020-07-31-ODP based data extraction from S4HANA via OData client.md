---
title: ODP based data extraction from S/4HANA via OData client
origurl: https://github.com/ROBROICH/SAP_ODP_ODATA_CLIENT
medium: github repos #blog, github repos, linkedIn article, partner pages
date: 2020-07-31 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DATA_EXTRACTION, AZURE_DATA_FACTORY] # category should be a topic and sub-category primary product
tags: [odp, odata, cds-view, getting-started]     # TAG names should always be lowercase

author:
  name: Roman Broich
  link: https://www.linkedin.com/in/roman-broich/

comments: false

pin: false
---

For data extraction scenarios from S/4HANA the following requirements have typically to be met:

Logical data models abstracting the complexity SAP source tables and corresponding columns
The data source must be delta-/CDC-enabled to avoid full delta loads
Open interfaces and protocols to support the customer demand for cloud-based architectures.
Support of frequent intraday data-loads instead of nightly batches
Supports the extraction of transactional and master data
The updated ODP-OData feature in SAP NW 7.5 is the enabling technology for achieving the requirements describe above. Further references: New ODP feature in SAP NetWeaver 7.5

This document will describe the required step to enable the OData-based consumption of changed records in a SAP S/4HANA system.
