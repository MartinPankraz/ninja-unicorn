---
title: From zero to hero security coverage with Microsoft Sentinel for your critical SAP security signals – Part 2
origurl: https://blogs.sap.com/2023/05/23/from-zero-to-hero-security-coverage-with-microsoft-sentinel-for-your-critical-sap-security-signals-part-2/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-05-22 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, SENTINEL] # category should be a topic and sub-category primary product
tags: [soar,security,logic-apps,s4,getting-started,siem,sec-ops]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Dear community,

Based on part 1 of this series we are going to up-level to more sophisticated automation to block compromised SAP users. The basic playbook discussed before served the purpose of getting started quickly. On the downside it compromised on scalability.

Today’s post is about completing that workflow with secure credential handling and dynamic parameter setting with watchlists.
