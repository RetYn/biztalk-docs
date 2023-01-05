---
description: "Learn more about: Locally Initiated Conversations"
title: "Locally Initiated Conversations1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 626d4130-f3b7-40b6-92ba-ef9526125433
caps.latest.revision: 3
author: "christopherhouser"
ms.author: "test"
manager: "anneta"
---
# Locally Initiated Conversations
Conversations are initiated locally by issuing an [ALLOCATE](./allocate2.md) or [MC_ALLOCATE](./mc-allocate2.md) verb. The **ALLOCATE** and **MC_ALLOCATE** verbs are modified to support additional parameters required by Sync Point support. The supplied **synclevel** parameter of the **ALLOCATE** and **MC_ALLOCATE** verbs can take on a value of AP_SYNCPT, which specifies that the conversation requested is a Sync Point conversation.
