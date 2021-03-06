---
title: "Codeunit Object"
description: "Description of the codeunit object."
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 10/01/2018
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
ms.assetid: a0ac492d-e3c8-4a76-87b4-b469e08c58e7
ms.author: solsen
caps.latest.revision: 18
---

[!INCLUDE[d365fin_dev_blog](includes/d365fin_dev_blog.md)]

# Codeunit Object
A codeunit is a container for AL code that you can use in many application objects. 

## Snippet support
Typing the shortcut `tcodeunit` will create the basic layout for a codeunit object when using the [!INCLUDE[d365al_ext_md](../includes/d365al_ext_md.md)] in Visual Studio Code.

## Codeunit example
This codeunit example checks whether a given customer has registered a shoesize. If not, the customer is assigned a shoesize of 42.

```
codeunit 50113 CreateCustomer
{
    trigger OnRun();
    var
        r: record Customer;
    begin
        if not r.HasShoeSize() then
            r.ShoeSize := 42;
    end;
}

```

## See Also
[Developing Extensions](devenv-dev-overview.md)  
[Table Extension Object](devenv-table-ext-object.md)  
[Page Extension Object](devenv-page-ext-object.md)  
[AL Development Environment](devenv-reference-overview.md)
