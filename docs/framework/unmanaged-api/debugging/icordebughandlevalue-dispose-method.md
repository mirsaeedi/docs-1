---
title: "ICorDebugHandleValue::Dispose Method"
ms.date: "03/30/2017"
api_name: 
  - "ICorDebugHandleValue.Dispose"
api_location: 
  - "mscordbi.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "ICorDebugHandleValue::Dispose"
helpviewer_keywords: 
  - "ICorDebugHandleValue::Dispose method [.NET Framework debugging]"
  - "Dispose method [.NET Framework debugging]"
ms.assetid: c1542811-0a7f-4235-bcfd-b24370d6f24b
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# ICorDebugHandleValue::Dispose Method
Releases the handle referenced by this ICorDebugHandleValue object without explicitly releasing the interface pointer.  
  
## Syntax  
  
```  
HRESULT Dispose ();  
```  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]
