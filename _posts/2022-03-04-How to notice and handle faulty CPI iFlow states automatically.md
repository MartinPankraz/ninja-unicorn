---
title: How to notice and handle faulty CPI iFlow states automatically
origurl: https://blogs.sap.com/2022/03/04/how-to-notice-and-handle-faulty-cpi-iflow-states-automatically/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-03-04 10:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [MONITORING, LOGIC_APPS] # category should be a topic and sub-category primary product
tags: [cpi, sap-btp, integration-suite, logic-apps, monitor-workbooks, alert-notification-service]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

some of you are already using my proposed architecture to externally monitor iFlow executions and messages with Azure Workbooks by forwarding the Message Processing Log. But what if your iFlow or CPI tenant fails altogether? In case you rely on regular CPI Cockpit check-ins by your Admins it can take days or require a customer call because the integration does not send any data anymore to make you aware.
