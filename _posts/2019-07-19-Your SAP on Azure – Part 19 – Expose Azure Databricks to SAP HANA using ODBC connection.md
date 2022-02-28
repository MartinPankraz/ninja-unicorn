---
title: Your SAP on Azure – Part 19 – Expose Azure Databricks to SAP HANA using ODBC connection
origurl: https://blogs.sap.com/2019/07/18/your-sap-on-azure-part-19-expose-azure-databricks-to-sap-hana-using-odbc-connection/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-07-19 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
The use cases for the Hadoop and SAP HANA are different, but in some cases, it is recommended or even required or to connect both worlds. The Hadoop clusters operate on very large datasets that consist of unstructured data while SAP HANA is focused on analytical processing. An ETL process that would replicate the Hadoop data is not always a good solution as it could dramatically increase the database memory requirements. But a smart usage of both technologies benefits from lower storage cost and high-speed in-memory processing power at the same time.
