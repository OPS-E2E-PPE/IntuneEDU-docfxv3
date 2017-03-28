---
# required metadata

title: What is Intune for Education?
titleSuffix: Intune for Education
description:
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 03/24/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: c66e1700-aac0-44c0-af89-d5d9d4fac9ae
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: [ALIAS]
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# What is Intune for Education?

Microsoft Intune for Education is a cloud-based device and app management service that can be used to quickly configure and manage Windows 10 devices for schools and other learning environments. Intune for Education is designed for schools who want to put devices in classrooms and not touch them for the rest of the school year. It makes it easy for professional IT admins, or teachers acting as IT for their classroom, to get up-and-running in minutes with Windows 10 devices.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ukrnCwcLvV8" frameborder="0" allowfullscreen></iframe>

 With Intune for Education, you can:
- Save teachers' time when using shared and individual Windows 10 devices
- Improve student learning outcomes through connected classrooms and engaging new technologies
- Integrate with [existing Student Information Systems](../get-started/what-is-school-data-sync.md)
- Optimize devices for testing

Intune for Education works closely with Azure Active Directory (Azure AD), Microsoft School Data Sync, and Office 365 to simplify device management.

## How is Intune for Education different from Microsoft Intune?
Intune for Education is designed to meet the specific needs of schools and school districts, . The table below helps identify which version of Intune to use:

| Intune for Education         | Intune           |
| ------------- |-------------|
|- Exclusively Windows 10 devices<br>- Basic Intune capabilities (no VPN, EDP, etc.)   |-  Non-Windows 10 devices (i.e. iOS or Android)</br>- Advanced management needs |

## Will Intune for Education work for shared devices?
Intune for Education manages multiple users on a single device. With Intune for Education, when users sharing a device have different apps and settings targeted to them, the user who is logged on sees only the apps and settings setup for them.

<!-- Intune for Education integrates with other products in the Microsoft Education system. To learn more about our other products see <pending>. -->

## Get started with Intune for Education

To get started with Intune for Education, open the [Intune for Education console](https://manage.windowsazure.com) and login with your school credentials. You will see a special version of the Azure management portal where you can access Intune for Education.  No need to worry about virtual machines, Azure networking, or other Azure capabilities. Our goal is to make it simple for you to take care of your critical tasks.

After you log in, you'll see our [Express Configuration](../get-started/express-configuration.md), a workspace to help get you up and running. There you can select a group containing students' or teachers' devices and start deploying apps and settings. We automatically add Intune for Education as a management tool to your Windows Store tenant and to Azure Active Directory (AD) to simplify getting started.

<!--

>[&larr; **Add apps**](.\add-apps.md)      [**Get Started** &rarr;](..\get-started\get-started.md) -->