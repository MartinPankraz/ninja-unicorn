---
title: Exposing SAP legacy middleware with Azure PaaS securely
origurl: https://docs.microsoft.com/azure/virtual-machines/workloads/sap/expose-sap-process-orchestration-on-azure
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-07-22 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, AZURE_APPLICATION_GATEWAY] # category should be a topic and sub-category primary product
tags: [sap-btp, front-door, app-gateway, firewall, sap-pi, sap-po, reverse-proxy]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Enabling internal systems and external partners to interact with SAP backends is a common requirement. Existing SAP landscapes often rely on the legacy middleware SAP Process Orchestration(PO) or Process Integration(PI) for their integration and transformation needs. For simplicity the term "SAP Process Orchestration" will be used in this article but associated with both offerings.

This article describes configuration options on Azure with emphasis on Internet-facing implementations.
