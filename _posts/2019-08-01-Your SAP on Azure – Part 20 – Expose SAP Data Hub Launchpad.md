---
title: Your SAP on Azure – Part 20 – Expose SAP Data Hub Launchpad
origurl: https://blogs.sap.com/2019/08/01/your-sap-on-azure-part-20-expose-sap-data-hub-launchpad/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-08-01 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
When you deploy the SAP Data Hub to Azure you need to consider how to access it. Of course, you can always enter a node URL and the port in the browser, but that’s not the recommended scenario. After a system restart (or even during normal work) the node assignment can change. It would mean that all your links stop working and users are not able to access the system.
