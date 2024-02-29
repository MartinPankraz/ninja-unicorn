---
title: SAP GUI MFA with SAP Secure Login Service and Microsoft Entra ID
origurl: https://community.sap.com/t5/technology-blogs-by-members/sap-gui-mfa-with-sap-secure-login-service-and-microsoft-entra-id/ba-p/13605383
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2024-02-26 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, AZURE_AD] # category should be a topic and sub-category primary product
tags: [aad,sap-ias,sap-btp,entra-id,sap-secure-login-service,mfa,sap-gui]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://community.sap.com/t5/user/viewprofilepage/user-id/171519

comments: false

pin: false
---
This blog post guides you through the setup of an end-to-end scenario for implementing [multi-factor authentication](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks) (MFA) for SAP GUI with Microsoft Entra ID (formerly known as Microsoft Azure Active Directory, AAD). The integration with Microsoft Entra ID is accomplished by [SAP Cloud Identity Service](https://help.sap.com/docs/identity-authentication) and the [SAP Secure Login Service for SAP GUI](https://help.sap.com/docs/SAP%20SECURE%20LOGIN%20SERVICE/c35917ca71e941c5a97a11d2c55dcacd/28d654c4459d4693bbf34e5103867f97.html?locale=en-US). Kudos to [@Christian_Cohrs](https://community.sap.com/t5/user/viewprofilepage/user-id/181868) for supporting the setup of the test environment and thoroughly reviewing this blog post.
