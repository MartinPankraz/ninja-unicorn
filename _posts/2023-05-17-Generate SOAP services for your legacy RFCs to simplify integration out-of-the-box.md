---
title: Generate SOAP services for your legacy RFCs to simplify integration out-of-the-box
origurl: https://blogs.sap.com/2023/05/17/generate-soap-services-for-your-legacy-rfcs-to-simplify-integration-out-of-the-box/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-05-17 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, SENTINEL] # category should be a topic and sub-category primary product
tags: [soar,security,logic-apps,s4,getting-started,siem,sec-ops,soap,rfc,playbook]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Dear community,

supporting my post about “Security Orchestration, Automation, and Response” for SAP, I am sharing a step by step guide to expose your legacy RFCs as enterprise services (SOAP) through configuration. No development needed! However, an ABAP developer key is required to activate the enterprise service 🤷🏽‍♀️🙃

This way the RFC capabilities may be handled by API Management, workflow engines like SAP Build Process Automation, SAP Cloud Integration or Azure Logic Apps without special runtimes.

Such an approach is still useful, because some nice SAP remote function modules just don’t have a nice SOAP or OData interface today or maybe ever. S/4HANA Cloud anyone?
