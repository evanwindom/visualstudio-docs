---
title: "How to: Enable and Disable Edit and Continue | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "CSharp"
  - "VB"
  - "FSharp"
  - "C++"
helpviewer_keywords: 
  - "/INCREMENTAL linker option"
  - "Apply Code Changes command"
  - "Edit and Continue, disabling"
  - "code changes, applying in break mode"
  - "INCREMENTAL linker option"
  - "Edit and Continue, enabling"
  - "break mode, applying code changes"
  - "Edit and Continue, applying code changes"
  - "Step command"
  - "Go command"
ms.assetid: fd961a1c-76fa-420d-ad8f-c1a6c003b0db
caps.latest.revision: 26
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# How to: Enable and Disable Edit and Continue
You can disable or enable Edit and Continue in the **Options** dialog box at design time. You cannot change this setting while you are debugging.  
  
 Edit and Continue works only in debug builds. For native C++, Edit and Continue requires using the /INCREMENTAL option.  
  
## Procedures  
  
#### To enable/disable Edit and Continue  
  
1.  Open debugging options page (**Tools / Options / Debugging**).  
  
2.  Scroll down to **Edit and Continue** category.  
  
3.  To enable, select the **Enable Edit and Continue** check box. To disable, clear the check box.  
  
    > [!NOTE]
    >  If IntelliTrace is enabled and you collect both IntelliTrace events and call information, Edit and Continue is disabled. For more information, see [Configure IntelliTrace](http://msdn.microsoft.com/en-us/7657ecab-e07e-4b1b-872d-f05d966be37e).  
  
4.  Click **OK**.  
  
 For more information about these options, see [General, Debugging, Options Dialog Box](../debugger/general-debugging-options-dialog-box.md).  
  
## See Also  
 [Edit and Continue](../debugger/edit-and-continue.md)