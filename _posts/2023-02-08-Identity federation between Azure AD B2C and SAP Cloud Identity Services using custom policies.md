---
title: Identity federation between Azure AD B2C and SAP Cloud Identity Services using custom policies
origurl: https://blogs.sap.com/2023/02/08/identity-federation-between-azure-ad-b2c-and-sap-cloud-identity-services-using-custom-policies/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2023-02-08 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, AZURE_AD] # category should be a topic and sub-category primary product
tags: [aad,ias,sap-btp,aad-b2c]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---
[SAP Cloud Identity Services, Identity Authentication](http://help.sap.com/docs/IDENTITY_AUTHENTICATION/6d6d63354d1242d185ab4830fc04feb1/d17a116432d24470930ebea41977a888.html?locale=en-US) (IAS), can act as an identity provider to authenticate users managed in its own local user store, or delegate authentication to an existing corporate identity provider and directory. Many companies choose the latter option to setup identity federation between their tenants in IAS and Microsoft Azure Active Directory (Azure AD) to offer single sign-on (SSO) to corporate users and allow them to authenticate with their known credentials. Detailled setup instructions for Azure AD are well covered by [SAP](https://developers.sap.com/tutorials/cp-ias-azure-ad.html)‘s and [Microsoft](https://learn.microsoft.com/en-us/azure/active-directory/saas-apps/sap-hana-cloud-platform-identity-authentication-tutorial)‘s product documentation and related blog posts on this topic.
