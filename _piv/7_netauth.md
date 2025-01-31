---
layout: page
collection: piv
title: Introduction to Network Authentication Guides
permalink: piv/network/
sticky_sidenav: true
sidenav: piv

subnav:
  - text: Ports and Protocols
    href: ../../piv/network/ports/
  - text: Domain Controllers
    href: ../../piv/network/dc/
  - text: Trust Stores
    href: ../../piv/network/trust-stores/
  - text: Account Linking
    href: ../../piv/network/account/
  - text: Group Policies and Enforcement
    href: ../../piv/network/group/
  - text: Network Tuning
    href: ../../piv/network/tuning/
  - text: Local Certification Authority
    href: ../../piv/network/localca/
  - text: Authentication Assurance
    href: ../../piv/network/auth/
  - text: PIV Auth on macOS
    href: ../../piv/network/mac/
---

These Network Authentication guides will help you configure your Windows _network domain_ for smart card logon using PIV credentials.

There are many useful pages and technical articles available online that include details on configurations and using generic smart cards.  The information presented here addresses common questions and configurations **specific** to the U.S. federal government, **PIV** smart cards, and U.S. federal civilian agency certification authorities.

{% include alert-info.html heading = "Teamwork" content="Work with your Network Engineers, Domain Admins, Account Management, and Information Security colleagues to review the information, perform the configurations, and troubleshoot any issues." %}

## Pre-Launch Checklist

Check the following items **before** reviewing these network guides and lessons learned:

1. Users have PIV credentials and PIV card readers.
1. You are using Microsoft Active Directory to manage your Windows network.
1. Domain Controllers are Microsoft 2008 R2 or 2012 or above.
1. User workstations **are joined** to your network and are Windows 7, Windows 8, or Windows 10-based.

## Configuration Checklist

There are five configuration categories to review with your colleagues.  All five include steps that must be completed; it's best to review and complete the configuration categories in this order:    

- [Network Ports and Protocols](../network/ports/)
- [Domain Controllers](../network/dc/)
- [Trust Stores](../network/trust-stores/)
- [Account Linking: Associating PIV credentials with User Accounts](../network/account/)
- [Group Policies and Enforcement](../network/group/)

There are three additional guides:

- [Network Tuning](../network/tuning/)
- [Local Certification Authority](../network/localca/)
- [Authentication Assurance](../network/auth/)

We want to add additional information for installing Online Certificate Status Protocol (OCSP) services, adressing common errors and troubleshooting, and configuring MacOSX and other operating systems.  

Submit an [Issue]({{site.repourl}}/issues/new){:target="_blank"}{:rel="noopener noreferrer"} to identify information that would be helpful to you, or consider contributing a page to these guides with your lessons learned.   


