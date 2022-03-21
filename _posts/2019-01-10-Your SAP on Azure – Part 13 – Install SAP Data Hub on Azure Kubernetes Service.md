---
title: Your SAP on Azure – Part 13 – Install SAP Data Hub on Azure Kubernetes Service
origurl: https://blogs.sap.com/2019/01/10/your-sap-on-azure-part-13-install-sap-data-hub-on-azure-kubernetes-service/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-01-10 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [dummy, dummy] # category should be a topic and sub-category primary product
tags: [dummy]     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
SAP Data Hub is one of the newest SAP products that integrates data from multiple sources. It’s fully containerized which means that each application component runs in a separate environment. The architecture is completely different to SAP Netweaver, so there is a lot of learning ahead of us. To run the SAP Data Hub you will require a Kubernetes service to manage the deployed containers. You can use an on-premise solution like SUSE CaaS, but I recommend having a look at the Azure Kubernetes Service and deploy the SAP Data Hub in the cloud!
