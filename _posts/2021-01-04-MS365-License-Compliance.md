---
layout: post
title: MS365 License Compliance
subtitle: Subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [ms365, license]
comments: true
---

I'm currently working as an IT consultant for an IT outsourcing company. My work is normally regarding Microsoft 365, Azure and Windows Servers/Clients.

Lately I’ve worked, a lot with the “Microsoft 365 Business Premium” or “Microsoft 365 E3” license and services.

While working with license in Microsoft 365 / Azure AD, I’ve experienced the success and ease of using Azure AD license groups for license control (Maybe I’ll make a post about this later). But I’ve also experienced the pain and frustration about Microsoft 365 license compliance and mixed license (Which it’s seems Microsoft didn’t bother creating a tool for), because my customers turns to me (As an expert) for the correct advice and expected me to recommend the correct Microsoft 365 licenses which of cause is a complaint “Package” (At that point in time).

I then found this session from directionsonmicrosoft and thought that I might be able to create script, tell me if a customer’s tenant is complaint. [https://www.directionsonmicrosoft.com/sites/default/files/samples/webinars/2019-10-24_Microsoft_365_Hidden_Licensing_Costs/presentation_html5.html)](https://www.directionsonmicrosoft.com/sites/default/files/samples/webinars/2019-10-24_Microsoft_365_Hidden_Licensing_Costs/presentation_html5.html)

I’ve worked on the script for some weeks, and it seems it’s ready for some alpha runs. The script can be found at [https://github.com/ingildsens/ms365-license-tools/blob/main/reportCheckIfLicenseGroupIsComplaint.ps1](https://github.com/ingildsens/ms365-license-tools/blob/main/reportCheckIfLicenseGroupIsComplaint.ps1) .

Bonus: I’ve also created the script [https://github.com/ingildsens/ms365-license-tools/blob/main/reportCalculateCheapestPlanCombination.ps1](https://github.com/ingildsens/ms365-license-tools/blob/main/reportCalculateCheapestPlanCombination.ps1) which is used to determine the cheapest license combination for a license group.