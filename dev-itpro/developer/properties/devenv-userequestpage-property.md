---
title: "UseRequestPage Property"
ms.custom: na
ms.date: 12/19/2018
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---

# UseRequestPage Property
Sets whether a request page is presented to the user.  
  
## Applies To  
  
- Reports  
  
- XMLports  
  
## Property Value  
 **True** if you want to show a request page; otherwise, **false**. The default is **true**.  
  
## Remarks  
If UseRequestPage is **false**, then a request page is not shown. The user cannot choose a sort order or set filters. In the [!INCLUDE[prodlong](../includes/prodlong.md)] Web client, Request pages are not supported. If you try to run an XMLport with a Request page from the Web client, you receive an error that the XMLport page type is not supported. To run an XMLport without using a Request page, this property must be set to **false**.
  
You can override the setting of the UseRequestPage property at runtime by setting the *ReqWindow* parameter of the [REPORT.RUN Method](../methods/devenv-report-run-method.md), [REPORT.RUNMODAL Method](../methods/devenv-report-runmodal-method.md), or [RUN Method (XMLport)](../methods/devenv-run-method-XMLport.md).