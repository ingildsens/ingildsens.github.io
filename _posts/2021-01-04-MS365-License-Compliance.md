---
layout: post
title: MS365 License Compliance
subtitle: Subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [ms365, license]
comments: true
---


I'm currently working as an IT consultant for an IT outsourcing company. My work normally revolves around Microsoft 365, Azure and Windows Servers/Clients.

Lately, I’ve worked a lot with the “Microsoft 365 Business Premium” or “Microsoft 365 E3” license and services.

While working with Microsoft365/Azure AD licenses, I've experienced the ease of using Azure AD license groups for license control (Maybe I’ll make a post about this later). But I’ve also experienced the pain and frustration about Microsoft 365 license compliance and mixed license, which Microsoft have not cared to make a tool for. When customers come to me, as an expert, for sound advice, they expect me to recommend the correct Microsoft365 licenses, which "of course" consist of a "compliance package" (at this point in time).

After a while I found this session from directionsonmicrosoft where they explain the “Microsoft 365 Hidden Licensing”. After watching the session I thought, I might be able to create script, that tells you whether or not a customer's tenant is compliant. [https://www.directionsonmicrosoft.com/sites/default/files/samples/webinars/2019-10-24_Microsoft_365_Hidden_Licensing_Costs/presentation_html5.html](https://www.directionsonmicrosoft.com/sites/default/files/samples/webinars/2019-10-24_Microsoft_365_Hidden_Licensing_Costs/presentation_html5.html)

I’ve worked on the script for some weeks, and it seems to be ready for some alpha runs. The script can be found at [https://github.com/ingildsens/ms365-license-tools/blob/main/reportCheckIfLicenseGroupIsComplaint.ps1](https://github.com/ingildsens/ms365-license-tools/blob/main/reportCheckIfLicenseGroupIsComplaint.ps1) .

Bonus: I’ve also created this script, which is used to determine the cheapest license combination for a license group. [https://github.com/ingildsens/ms365-license-tools/blob/main/reportCalculateCheapestPlanCombination.ps1](https://github.com/ingildsens/ms365-license-tools/blob/main/reportCalculateCheapestPlanCombination.ps1)
