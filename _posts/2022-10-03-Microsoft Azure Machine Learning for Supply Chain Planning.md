---
title: Microsoft Azure Machine Learning for Supply Chain Planning
origurl: https://blogs.sap.com/2022/10/03/microsoft-azure-machine-learning-for-supply-chain-planning/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-10-03 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, AZURE_ML] # category should be a topic and sub-category primary product
tags: [ibp,sap-btp,azure-ml,machine-learning,cpi,excel,]     # TAG names should always be lowercase

author:
  name: Domnic Savio Benedict
  link: https://people.sap.com/domnicsavio.benedict

comments: false

pin: false
---
The flexibility of bringing your own logic into your planning cycles encourages developers to work closely with planners and experiment different algorithms. This also raises a question — where do you like to run your external algorithms?. It is at the liberty of the customer or developer, which platform he or she chooses. In this blog, I would like to share my experience on using Microsoft’s Azure Machine Learning s a platform. In the 2205 release of SAP Integrated Business Planning for Digital Supply Chain, new oData API’s were introduced to extract planning data and apply external algorithms to it and influence a forecast plan. This [blog describes](https://blogs.sap.com/2022/05/11/how-to-forecast-using-custom-external-algorithms/) it in detail.  I already explained [how one could use Google’s Vertex AI](https://blogs.sap.com/2022/06/21/google-vertex-ai-for-supply-chain-planning/) to do this job as an external platform. In this blog, I am using Microsoft’s Azure Machine Learning to do the forecast with a similar data set. The aim of this task is definitely not focused on the performance validation of different platforms, rather,
