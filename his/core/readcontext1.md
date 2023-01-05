---
description: "Learn more about: ReadContext"
title: "ReadContext1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: d81c496f-a6b5-427b-b5c0-9ce00573ad6a
caps.latest.revision: 3
author: "christopherhouser"
ms.author: "test"
manager: "anneta"
---
# ReadContext
Use the **ReadContext** method to acquire the value of an entry in a TI Context array.  
  
## Syntax  
  
```  
  
HRESULT ReadContext (  
```  
  
#### Parameters  
 *bstrContextEntryName*  
 This string parameter contains the name of the TI Context entry to be retrieved.  
  
 *pvarContextEntryValue*  
 This VARIANT parameter contains the value of the context entry identified by bstrContextEntryName.  
  
 *prgContextArray*  
 This SAFEARRAY parameter contains the TI Context entries that are passed to and returned from COM+ objects.  
  
## Return Codes  
 S_OK  
 The method call completed successfully.  
  
 E_INVALIDARG  
 One or more of the parameters passed are invalid.  
  
 E_FAIL  
 An internal processing error occurred.  
  
## See Also  
 [ClearAllContext](../core/clearallcontext1.md)   
 [ClosePersistentConnection](../core/closepersistentconnection1.md)   
 [CountContext](../core/countcontext1.md)   
 [DeleteContext](../core/deletecontext2.md)   
 [GetConnectionInfo](../core/getconnectioninfo2.md)   
 [QueryContextInfo](../core/querycontextinfo1.md)   
 [UpdateContextInfo](../core/updatecontextinfo1.md)   
 [WriteContext](../core/writecontext1.md)   
 [Persistent Connections](./persistent-connections2.md)
