---
title: Microsoft Sentinel for SAP goes agentless
origurl: https://community.sap.com/t5/enterprise-resource-planning-blogs-by-members/microsoft-sentinel-for-sap-goes-agentless/ba-p/13960238
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2024-12-17 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, Sentinel] # category should be a topic and sub-category primary product
tags: [sentinel,xdr,agentless,security,s4,getting-started,siem,audit-log]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://community.sap.com/t5/user/viewprofilepage/user-id/143781

comments: false

pin: false
---
Having a turn-key solution as much as possible leads to better adoption of SAP security. Agents running in Docker containers, Kubernetes, or other self-hosted solutions are not for everyone.

Microsoft Sentinel for SAP’s latest capability re-uses the SAP Cloud Connector to profit from already existing setups, established integration processes, and well-understood SAP components. Bazinga!

The new integration path leverages SAP Integration Suite to connect Microsoft Sentinel with your SAP systems. The Cloud integration capability of SAP Integration Suite speaks all relevant protocols, has connectivity into all the places where your SAP systems might live, is strategic for most SAP customers, and is fully SAP RISE compatible by design.
