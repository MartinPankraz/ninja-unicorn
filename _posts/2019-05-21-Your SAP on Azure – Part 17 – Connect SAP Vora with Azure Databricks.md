---
title: Your SAP on Azure – Part 17 – Connect SAP Vora with Azure Databricks
origurl: https://blogs.sap.com/2019/05/21/your-sap-on-azure-part-17-connect-sap-vora-with-azure-databricks/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-05-21 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [, ] # category should be a topic and sub-category primary product
tags: []     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
As soon as I finished my earlier post about the integration of the SAP Vora with the Azure HDInsight I started to wonder if it would be possible to reuse the Spark Extension with the Azure Databricks. It’s a new analytics platform based on the Apache Spark that enables an active collaboration between data scientists, technical teams and the business. It offers a fully managed Spark clusters that can be created within seconds and automatically terminated when not used. It can even scale up and down depending on the current utilization. As all Azure services, the Databricks natively connects to other cloud platform services like the Data Lake storage or Azure Data Factory. A big differentiator comparing to HDInsight is a tight integration with Azure AD to manage users and permissions which increase the security of your landscape.
