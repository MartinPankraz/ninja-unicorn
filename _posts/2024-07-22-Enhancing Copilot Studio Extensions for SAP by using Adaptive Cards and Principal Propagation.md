---
title: Enhancing Copilot Studio Extensions for SAP by using Adaptive Cards and Principal Propagation
origurl: https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/enhancing-copilot-studio-extensions-for-sap-by-using-adaptive/ba-p/4187096
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2024-07-22 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [INTEGRATION, COPILOT] # category should be a topic and sub-category primary product
tags: [azure-openai,power-automate,copilot,odata,azure-openai-studio,principal-propagation]     # TAG names should always be lowercase

author:
  name: Noopur Vaishnav
  link: https://techcommunity.microsoft.com/t5/user/viewprofilepage/user-id/2501294

comments: false

pin: false
---
In the [previous blog](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/streamlining-sap-processes-with-azure-openai-copilot-studio-and/ba-p/4164338), SAP connectivity from the Copilot Studio and Power Platform were explored, let’s now look at an enhanced version of the scenario highlighted previously.

Let’s say, you are a salesperson that realizes that a material in a sales order is not available and want to help replace the unavailable item for the customer using a Copilot. You then try to do the following:

You ask the Copilot to help look through all the materials in the SAP system and find the best replacement.
You get a suitable replacement suggestion from Copilot and try to access material stock information for that material. However, you, as a salesperson are not able to access that information as you do not have the right authorization to do so in the SAP system.
You message your colleague who does have the authorization to check material stock information for you. The colleague checks the stock information and informs you that the material is in stock.
You then decide to update the sales order with the new material and remove the old material from the sales order.
Here is a video which demonstrates the scenario and how it has been enhanced from the previous blog. 
