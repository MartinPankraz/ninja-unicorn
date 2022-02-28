---
title: Your SAP on Azure – Part 5 – ASCS High Availability with Storage Spaces Direct
origurl: https://blogs.sap.com/2018/03/07/your-sap-on-azure-part-5-ascs-high-availability-with-storage-spaces-direct/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2018-03-18 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
We can now use the file share instead of the shared cluster disk for the Central Services instance and Microsoft released a feature Storage Spaces Direct (S2D) that implements a software-defined storage in Windows 2016. Those two innovations have a major impact on designing fault-tolerant solutions. You can deploy the entire solution in Microsoft Azure and eliminate the need of buying SIOS DataKeeper or Starwind licenses that simulate the SAN drive.
