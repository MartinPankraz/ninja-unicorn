---
title: Principal propagation in a multi-cloud solution between Microsoft Azure and SAP Business Technology Platform (BTP), Part IV SSO with a Power Virtual Agents Chatbot and On-Premises Data Gateway
origurl: https://blogs.sap.com/2021/04/13/principal-propagation-in-a-multi-cloud-solution-between-microsoft-azure-and-sap-business-technology-platform-btp-part-iv-sso-with-a-power-virtual-agent-chatbot-and-on-premises-data-gateway/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2021-02-24 06:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, XSUAA] # category should be a topic and sub-category primary product
tags: [sap-btp, cf, aad, security, principal-propagation, cloud-connector, sap-gateway, app-service, power-virtual-agent, onpremises-data-gateway, teams, oauth]     # TAG names should always be lowercase

author:
  name: Martin Raepple
  link: https://people.sap.com/mraepple

comments: false

pin: false
---

## Implementing the Teams chatbot with Power Virtual Agents and Power Automate

Part III introduced a real-world business application to the scenario by adding a Microsoft Teams-based chat bot which allows the user to order new IT equipment from a product catalogue managed by the ABAP backend. The bot is implemented in C# using the Bot Framework Software Development Kit (SDK) along with the Azure Bot Service, which enables the classical or “pro-code” developer to create a compelling chat bot experiences. This includes single sign-on (SSO) from Teams and end-to-end principal propagation with the Azure AD-authenticated user when accessing the product data in the backend system. You can find the complete source code of the bot in GitHub. The dialog between the user and the bot is implemented as a Waterfall dialog from the SDK by defining the series of steps to collect information from the user and to guide her through a series of tasks.
