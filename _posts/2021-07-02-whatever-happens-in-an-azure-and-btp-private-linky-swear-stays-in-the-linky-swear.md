---
title: Whatever happens in an Azure and BTP private linky swear, stays in the linky swear! An implementation story of the Private Link Service for Azure.
origurl: https://blogs.sap.com/2021/07/02/whatever-happens-in-an-azure-and-btp-private-linky-swear-stays-in-the-linky-swear/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-07-02 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [NETWORKING, PRIVATE_LINK] # category should be a topic and sub-category primary product
tags: [getting-started, private-link, sap-btp, sap-bas, odata, cloud-sdk, java, cap]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---

Dear community,

With the release of the Beta of BTP Private Link Service (PLS) exciting times dawned upon us. We finally get a managed solution to securely connect from our Apps running on BTP (deployed on Azure) to any IaaS workload running on Azure without even traversing the internet. The first options that come to mind would be SAP WebDispatcher, ECC, S4, HANA, SAP CAR, anyDB, Jenkins, Apache or HPC cluster to name a few.
