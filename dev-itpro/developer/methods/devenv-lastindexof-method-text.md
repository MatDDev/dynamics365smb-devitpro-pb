---
title: "LASTINDEXOF Method"
ms.author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 10/01/2018
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 1
manager: edupont
author: SusanneWindfeldPedersen
redirect_url: /dynamics365/business-central/dev-itpro/developer/methods-auto/library
---

# LASTINDEXOF Method
Reports the one-based index position of the last occurrence of a specified string within this instance.  
```  
Index := Text.LASTINDEXOF(Value, [StartIndex])  
```  
## Parameters
*Value*    
&emsp;Type: Text  
The string to seek.  
  
*StartIndex*    
&emsp;Type: Integer  
The search starting position. The search proceeds from startIndex toward the beginning of this instance.  
  
## Return Value
*Index*  
&emsp;Type: Integer  
  
## See Also
[Text Data Type](../datatypes/devenv-text-data-type.md)  
[Getting Started with AL](../devenv-get-started.md)  
[Developing Extensions Using the New Development Environment](../devenv-dev-overview.md)  
