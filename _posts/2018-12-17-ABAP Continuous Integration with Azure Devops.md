---
title: ABAP Continuous Integration with Azure Devops – ABAP Unit in the Cloud
origurl: https://blogs.sap.com/2018/12/17/abap-continuous-integration-with-azure-devops-abap-unit-in-the-cloud/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2018-12-17 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [DEVOPS, AZURE_DEVOPS] # category should be a topic and sub-category primary product
tags: [ci-cd,abap,devops,github]     # TAG names should always be lowercase

author:
  name: Mattias Johansson
  link: https://people.sap.com/mattias.johansson2

comments: false

pin: false
---
We’re a SAP and Microsoft shop, running SAP CRM and also doing a lot of custom development in .Net on Azure. As part of an ongoing agile journey we will start working in vertical teams covering everything from UI (React), .Net, SAP and testing. One of our main goals is to be able to use the same process and tools as far as possible regardless of what environment the development is done in.

Since we’re a Microsoft shop we’re already using Azure Devops ( formely known as VSTS) as build server, and Sonarcloud for static code analysis.

In part 1 of this blog series I’m going to describe how we’ve integrated nightly ABAP Unit test runs into our Devops pipeline.
