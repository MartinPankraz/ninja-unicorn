---
title: SAP BTP ABAP Environment integration journey with Microsoft – Part 1
origurl: https://blogs.sap.com/2023/06/20/sap-btp-abap-environment-integration-journey-with-microsoft-part-1/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-06-20 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, EXCEL] # category should be a topic and sub-category primary product
tags: [sap-btp,excel,abap,steampunk,abap-cloud,apim,power-automate,odata,power-query,embedded-steampunk,principal-propagation]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Hello and welcome to your ABAP Cloud with Microsoft integration journey. Part 0 of this series got you covered with the prerequisites to get your dev environment on Azure up and running.

Today we will be generating an OData service for a Travel App hosted on BTP ABAP environment and integrate that with Microsoft Excel with “live feeds” that can be refreshed from the client.
