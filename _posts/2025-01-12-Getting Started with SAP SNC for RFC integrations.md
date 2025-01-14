---
title: Getting Started with SAP SNC for RFC integrations
origurl: https://community.sap.com/t5/enterprise-resource-planning-blogs-by-members/getting-started-with-sap-snc-for-rfc-integrations/ba-p/13983462
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2025-01-12 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, SAP] # category should be a topic and sub-category primary product
tags: [sentinel,snc,security,s4,getting-started,onpremises-data-gateway,cloud-connector,logic-apps,purview,powerbi,data-factory,x509,certificate]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://community.sap.com/t5/user/viewprofilepage/user-id/143781

comments: false

pin: false
---
Many of you still rely heavily on the legacy SAP interface RFC. In my world that often means customers connecting their third-party services to SAP backends (AS ABAP). Securing a protocol such as SAP Remote Function Call (RFC) requires network layer protection.

Often Kerberos is discussed on this topic, because it allows the mapping of Windows-Known identities to SAP backend users. However, this post is about apps and technical connections using X.509 certs – not people. They complain less – and boringly but reliably behave the same way once configured properly:winking_face: Meet SAP Secure Network Communications (SNC).
