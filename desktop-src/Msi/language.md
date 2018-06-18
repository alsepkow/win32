---
Description: The Language data type is a text string containing one or more valid numeric language IDs. If there are two or more language IDs, they must be separated by commas.
ms.assetid: 9b0608d1-b6e8-4cf9-8119-3c2909156516
title: Language
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Language

The Language data type is a text string containing one or more valid numeric language IDs. If there are two or more language IDs, they must be separated by commas.

The Language data type is a 16-bit value that is the combination of a primary and sublanguage numeric IDs. The Primary LANGID comprises bits 0 through 9 while the subLanguage ID is bits 10 through 15. For a list of primary and sub language numeric identifiers, see the [Language Identifier Constants and Strings](https://msdn.microsoft.com/en-us/library/Dd318693(v=VS.85).aspx) topic.

For primary language IDs, the range 0x200 to 0x3ff is user definable. The range 0x000 to 0x1ff is reserved for system use. For sublanguage IDs, the range 0x20 to 0x3f is user definable. The range 0x00 to 0x1f is reserved for system use.

 

 


