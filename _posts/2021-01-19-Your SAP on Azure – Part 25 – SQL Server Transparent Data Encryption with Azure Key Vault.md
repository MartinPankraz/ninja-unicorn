---
title: Your SAP on Azure – Part 25 – SQL Server Transparent Data Encryption with Azure Key Vault
origurl: https://blogs.sap.com/2021/01/19/your-sap-on-azure-part-25-sql-server-transparent-data-encryption-with-azure-key-vault/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-01-19 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
SAP systems contain the company’s most confidential data. List of orders, production plans, sales forecasts, and what’s even more important the key financial data are hosted on SAP. Therefore, each organization should ensure that this information is kept in a secure way that makes it impossible to read in the case when an unauthorized party gets access to database files or backup media. Microsoft does a great job in protecting customers’ data – all information stored in Azure are by default encrypted at rest, so even if the attackers got access to the physical Azure hardware, they would not be able to make any use of it. For infrastructure workloads, customers can in addition decide to put another level of protection and encrypt virtual disks, which makes it impossible to read stored data without having an encryption key. But the disk encryption at-rest won’t help if the attacker receives access to your virtual machine and is able to make a copy of the database. Or if your database backup leaks. In such a case they can just restore the database on another server and access the data without any issue.
