---
# required metadata

title: What are policy settings?
titleSuffix: Intune for Education
description: Learn how to manage settings through Intune for Education policies.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 04/17/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tanmayb
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:


---

# What are policy settings?
_Policies_ are groups of settings that manage features on your devices. When you create a policy, it manages the settings on those

## Manage settings

Settings are managed on a per-group basis. You can manage the simple list of useful settings using [Express Configuration](what-are-settings.md#manage-settings-in-express-configuration) or view a full list of settings for a group for fine-tuning [while managing your groups](what-are-settings.md#manage-settings-for-groups).

Device settings apply to all devices in their group. Settings that are **Not configured** allow the user to define their settings on their devices themselves.

> [!NOTE]
> Intune for Education settings such as **Block** or **Allow** override the device’s settings. For example, if a device has a camera and that camera is enabled by default, but the group setting for that device has Camera set to **Block**, [then the camera on the device will be turned off](core-concepts.md#what-is-group-inheritance).

## Manage settings with Express Configuration

Express Configuration makes it easy for you to get started quickly, but can also help you make quick changes throughout the lifecycle of your devices.

  ![Express Configuration settings fix](./media/express-config-006-choose-settings.png)

1. In the [Intune for Education](https://intuneeducation.portal.azure.com) console, choose **Launch Express Configuration**. Review the **Welcome** page and choose **Get started**.
2. Review the **Get school information** page. If you've already added school information, choose **Next**.
3. Select the group whose settings you want to manage, and then choose **Next**.
4. Review the list of apps, and then choose **Next**.
5. On the **Settings** page, expand the categories of available settings:
  - [Basic device settings](available-settings.md#basic-device-settings)
  - [Microsoft Edge settings](available-settings.md#internet-browser-settings)
  - [Device update settings](available-settings.md#device-update-settings)
  - [Networking and connection settings](available-settings.md#networking-and-connectivity)
  - [App settings](available-settings.md#app-settings)
  - [Sign in settings](available-settings.md#sign-in-settings)

  Expand a category and toggle the control to modify settings, and then choose **Next**.
6. Review your choices and then choose **Finish** to save your changes update them on devices in the selected group.

## Manage settings for groups

Use the following steps to manage the full list of settings in Intune for Education:
1. In the [Intune for Education](https://intuneeducation.portal.azure.com) console, in the left-side navigation menu, choose **Groups**.
2. Select the group whose settings you want to manage. For a complete list, see [Available settings](what-are-settings.md).
3. Click **Settings** at the top of the page to view the full list of available settings.
4. Expand categories and modify individual settings for the selected group.
5. Click **Save** to save the changes for that group. Settings are automatically sent to devices in that group.

## Find out more

- [Find out more about the full range of policies in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)