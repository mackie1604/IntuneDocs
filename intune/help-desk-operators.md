---
title: Help desk troubleshooting portal 
titleSuffix: "Intune on Azure"
description: Help desk staff use the troubleshooting portal to solve users' technical problems  
keywords:
author: NathBarn
ms.author: NathBarn
manager: angrobe
ms.date: 05/30/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 1f39c02a-8d8a-4911-b4e1-e8d014dbce95

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: sumitp
#ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-azure
---
# Help users with the Troubleshooting portal in Microsoft Intune

[!INCLUDE[azure_portal](./includes/azure_portal.md)]

The troubleshooting portal lets help desk operators and Intune administrators view users and their devices, and perform tasks to resolve Intune technical problems.

## Add help desk operators
An Intune administrator can assign help desk operator permission to users. Help desk users can then view the Intune portal but cannot view or perform administrative tasks outside the troubleshooting workload.

1. As an Intune administrator login to Intune portal, and select **Intune roles**.
3. On the **Intune roles** workload, select **Help Desk Operator** and then select **Assign**.
4. Type an **Assignment name** (required), an **Assignment description** (optional), and then assign **Members (Groups)** and **Scope (Groups)**.
5. Members of the Help Desk Operator role can now use the troubleshooting portal.

For more information about Intune roles, see [Intune roles (RBAC)](role-based-access-control.md).

## Access the troubleshooting portal

Help desk staff and Intune administrators can access the troubleshooting portal in two ways:
- In the Intune portal, select **Troubleshoot**. Other workloads are visible in the left navigation blade, but unavailable.

![Screenshot of the Intune Troubleshoot workload with Select User link](media/help-desk-user.png)
- Open [http://aka.ms/intunetroubleshooting](http://aka.ms/intunetroubleshooting) in a web browser. Only the Troubleshoot portal is visible.

## Use the troubleshooting portal

In the troubleshooting portal, you can choose **Select user** to view a users' information. User information can help you understand the current state of users and their devices. The troubleshooting portal shows the following troubleshooting details:
- **Tenant status**
- **User status**
- **Devices**
- **Group membership**
- **App protection status**

Help desk users can also perform remote tasks on devices such as **Remote lock**.
