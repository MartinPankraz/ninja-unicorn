---
title: From zero to hero security coverage with Microsoft Sentinel for your critical SAP security signals – Part 3
origurl: https://blogs.sap.com/2023/05/23/from-zero-to-hero-security-coverage-with-microsoft-sentinel-for-your-critical-sap-security-signals-part-3/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-05-22 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, SENTINEL] # category should be a topic and sub-category primary product
tags: [soar,security,logic-apps,s4,getting-started,siem,sec-ops,audit-log]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Dear community,

There are various problematic attack vectors for SAP backends, but one is more prominent than others: SAP Audit Log deactivation ☠️. Maybe because SAP forensics people are practically blind or because it demos well at security conferences 🤪. Up to you to judge.

A recent conversation with a customer from the oil industry confirmed the need to release yet another playbook. This time specifically for the out-of-the-box analytic rule “Deactivation of Security Audit Log”.

Note the skipped approval step in Teams compared to part 1 of the blog series. The playbook was designed with the assumption in mind that such a critical event should be acted upon immediately without human intervention.
