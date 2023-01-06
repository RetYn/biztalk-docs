---
description: "Learn more about: Virus-Checking Tool Problems"
title: "Virus-Checking Tool Problems1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: f5f42294-985c-41cf-a370-dbd2ae25c380
caps.latest.revision: 4
author: "christopherhouser"
manager: "anneta"
---
# Virus-Checking Tool Problems
When you are running [!INCLUDE[hisHostIntServNoVersion](../includes/hishostintservnoversion-md.md)] with some independent software vendor virus checking tools, SNA link services might fail to start due to the following error:  
  
 Event 128: "Can't load IHV DLL xxx.dll"  
  
 where xxx.dll is the specific DLL  
  
 It is recommended that any "real-time scanning" options be disabled on the virus checker before starting Host Integration Server to prevent local file access slowdowns.
