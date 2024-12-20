---
title: SAP GUI MFA with Microsoft Entra (Part II) - Integration with Microsoft Entra Private Access
origurl: https://community.sap.com/t5/technology-blogs-by-members/sap-gui-mfa-with-microsoft-entra-part-ii-integration-with-microsoft-entra/ba-p/13691141
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2024-12-06 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, ENTRA_ID] # category should be a topic and sub-category primary product
tags: [entra-id-governance,sap-btp,sap-ias,sap-idm,private-access,global-secure-access,sap-secure-login-service]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://community.sap.com/t5/user/viewprofilepage/user-id/171519

comments: false

pin: false
---
This blog post describes an alternative MFA-solution for SAP GUI based on the Kerberos protocol. It uses Microsoft Entra Private Access (PA) instead of SLS and IAS to integrate with Entra ID and Entra CA. Entra PA, and its accomanying service Entra Internet Access, are unified under Global Secure Access (GSA) in the Microsoft Entra admin center. Both enforce an identity-centric Zero Trust Network Access (ZTNA) strategy. With ZTNA, access is granted per user to specific services or applications, whereas traditional technologies for secure network access, such as Virtual Private Networks (VPNs), grant access to an entire network.
