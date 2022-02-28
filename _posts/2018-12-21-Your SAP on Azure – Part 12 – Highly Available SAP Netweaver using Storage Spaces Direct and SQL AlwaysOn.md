---
title: Your SAP on Azure – Part 12 – Highly Available SAP Netweaver using Storage Spaces Direct and SQL AlwaysOn
origurl: 
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2018-12-21 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [, ] # category should be a topic and sub-category primary product
tags: []     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
Using file shares to host the system mount directory was introduced a couple months ago and since then the implementation got significantly easier. No more manual editing of profile parameter files – now everything is reflected during system provisioning. Recently I went through the process again and I think the changes are so big, that it’s worth revisiting my past post. As there are a few improvements on Azure side as well I decided to write a brand-new guide and include additional information about protecting the SQL Server using AlwaysOn availability groups. The file share is still provisioned using a combination of the Storage Spaces Direct and the Scale-Out File Server functionalities in Windows Server 2016. To simplify the setup and avoid building large and expensive landscapes I deployed all required components to just a two-node Failover Cluster.
