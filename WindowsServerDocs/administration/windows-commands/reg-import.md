---
title: reg import
description: Reference topic for **** - 

ms.prod: windows-server


ms.technology: manage-windows-commands

ms.topic: article
ms.assetid: 0be103de-08fc-4f02-b590-361782680b3e
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# reg import



Copies the contents of a file that contains exported registry subkeys, entries, and values into the registry of the local computer.



## Syntax

```
Reg import FileName
```

### Parameters

|Parameter|Description|
|---------|-----------|
|\<FileName>|Specifies the name and path of the file that has content to be copied into the registry of the local computer. This file must be created in advance by using **reg export**.|
|/?|Displays help for **reg import** at the command prompt.|

## Remarks

The following table lists the return values for the **reg import** operation.

|Value|Description|
|-----|-----------|
|0|Success|
|1|Failure|

## Examples

To import registry entries from the file named AppBkUp.reg, type:
```
reg import AppBkUp.reg
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)