---
description: Syntax rules for formulas.
seo-description: Syntax rules for formulas.
seo-title: Syntax for any expression
solution: Analytics
title: Syntax for any expression
topic: Data workbench
uuid: d22d3c53-991e-4a9f-83a1-5ccd52064459
index: y
internal: n
snippet: y
---

# Syntax for any expression{#syntax-for-any-expression}

Syntax rules for formulas.

* When in a formula, keywords are case sensitive and must be typed exactly as they appear. 
* When in a formula, metric, dimension, and filter names that include spaces must use underscores between words. For example: [!DNL Page_Views] 
* For strings within expressions, you must escape certain single quotation marks, double quotation marks, and backslashes. For example:

    * [!DNL “can’t”] is acceptable and does not need to be escaped, but [!DNL ‘can’t’] is unacceptable and must escaped as [!DNL ‘can\’t’]. 
    
    * [!DNL c:\windows] must be escaped as [!DNL c:\\windows].
