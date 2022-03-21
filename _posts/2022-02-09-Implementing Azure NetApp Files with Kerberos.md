---
title: Implementing Azure NetApp Files with Kerberos
origurl: https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/implementing-azure-netapp-files-with-kerberos/ba-p/3142010
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-02-09 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [STORAGE, ANF] # category should be a topic and sub-category primary product
tags: [aad, architecture, sso, storage, nfs, hana, kerberos, netapp]     # TAG names should always be lowercase

author:
  name: Ralf Klahr
  link: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/303327#profile

comments: false

pin: false
---

Encryption is a very big topic when it comes to data security especially in public clouds.
Azure NetApp Files (ANF) supports DES, Kerberos AES 128, and Kerberos AES 256 encryption types (from the least secure to the most secure). If you enable AES encryption, the user credentials used to join Active Directory must have the highest corresponding account option enabled that matches the capabilities enabled for your Active Directory.
