---
title: Automatic SAP BTP trust store certificate renewal with Azure Key Vault – or how to stop thinking about expiry dates once and for all
origurl: https://blogs.sap.com/2022/12/02/automatic-sap-btp-trust-store-certificate-renewal-with-azure-key-vault-or-how-to-stop-thinking-about-expiry-dates-once-and-for-all/
medium: blog #blog, github repos, linkedIn article, partner pages
date: 2022-12-02 12:00:00 +/0100
# PLEASE ensure consistent categories and tags to keep the search/filtering meaningful!
categories: [AUTOMATION, LOGIC_APPS] # category should be a topic and sub-category primary product
tags: [sap-btp,app-gateway,sap-pls,key-vault,certificate,automation]     # TAG names should always be lowercase

author:
  name: Martin Pankraz
  link: https://people.sap.com/martin-pankraz

comments: false

pin: false
---
Dear community,

Expiring TLS certificates create maintenance efforts all over the place and pose a security risk if not taken care of in time. Especially if the underlying private key was at risk. Furthermore, security guidelines advocate for shorter lifecycles. [GobalSign](https://www.globalsign.com/en/blog/maximum-ssltls-certificate-validity-now-one-year), [DigiCert](https://www.digicert.com/support/resources/faq/public-trust-and-certificates/how-long-are-tls-ssl-certificate-validity-periods) and other official Certificate Authorities (CA) enforced a maximum of 13 months in 2020. However, most people want a lifetime of multiple years to avoid being bugged about it as seldom as possible.
