---
title: Your SAP on Azure – Part 21 – Stream SAP data into Azure Event Hub using SAP Data Hub
origurl: https://blogs.sap.com/2019/08/07/your-sap-on-azure-part-21-stream-sap-data-into-azure-event-hub-using-sap-data-hub/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2019-08-07 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [, ] # category should be a topic and sub-category primary product
tags: []     # TAG names should always be lowercase

author:
  name: Bartosz Jarkowski
  link: https://people.sap.com/bjarkowski

comments: false

pin: false
---
Azure EventHubs is a fully managed service that allows exchanging messages between systems in real-time. It’s capable of receiving and processing millions of events per second. SAP Data Hub doesn’t directly support Azure EventHubs, but the connection can be established using Kafka protocol. In today’s post, I would like to show you how to provision the Azure service and how to configure the connection. At the end, I will also include my ABAP system to stream SAP data.
