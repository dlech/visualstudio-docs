---
title: "STEPUNIT | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "STEPUNIT"
helpviewer_keywords: 
  - "STEPUNIT enumeration"
ms.assetid: cb8441f2-f744-4e73-acfe-ae8542df9649
caps.latest.revision: 9
ms.author: "gregvanl"
manager: "ghogen"
---
# STEPUNIT
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [STEPUNIT](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/stepunit).  
  
Specifies the step unit for stepping.  
  
## Syntax  
  
```cpp#  
enum enum_STEPUNIT {   
   STEP_STATEMENT   = 0,  
   STEP_LINE        = 1,  
   STEP_INSTRUCTION = 2  
};  
typedef DWORD STEPUNIT;  
```  
  
```csharp  
enum enum_STEPUNIT {   
   STEP_STATEMENT   = 0,  
   STEP_LINE        = 1,  
   STEP_INSTRUCTION = 2  
};  
```  
  
## Members  
 STEP_STATEMENT  
 Steps by statement.  
  
 STEP_LINE  
 Steps by line.  
  
 STEP_INSTRUCTION  
 Steps by instruction.  
  
## Remarks  
 Passed as an argument to the [Step](../../../extensibility/debugger/reference/idebugprocess3-step.md) method.  
  
## Requirements  
 Header: msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)   
 [Step](../../../extensibility/debugger/reference/idebugprocess3-step.md)
