---
title: "Argument BasePath must be a path to a folder | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: b180ce60-ad57-41a6-a313-491d86d84cc7
caps.latest.revision: 8
author: "stevehoag"
ms.author: "shoag"
manager: "wpickett"
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
# Argument BasePath must be a path to a folder
The argument `BasePath` must consist of a path to a folder. You may be parsing a string incorrectly and supplying a value that is not recognized as a valid path.  
  
## To correct this error  
  
-   Check the value you are supplying for `BasePath` to make sure it is a valid path to a folder.  
  
## See Also  
 <xref:System.CodeDom.Compiler.TempFileCollection.BasePath%2A>   
 <xref:System.Resources.ResXResourceWriter.BasePath%2A>   
 <xref:System.Resources.ResXResourceReader.BasePath%2A>   
 [How to: Parse File Paths](../../visual-basic/developing-apps/programming/drives-directories-files/how-to-parse-file-paths.md)