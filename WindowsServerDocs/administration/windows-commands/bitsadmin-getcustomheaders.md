---
title: bitsadmin getcustomheaders
description: "Windows Commands topic for **bitsadmin getcustomheaders** - Retrieves the custom HTTP headers from the job."
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 1f0d38d3-e865-4474-81e8-773d65c3d1cc
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016 
---
# bitsadmin getcustomheaders

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Retrieves the custom HTTP headers from the job.

## Syntax

```
bitsadmin /GetCustomHeaders <Job>
```

## Parameters

|Parameter|Description|
|-------|--------|
|Job|The job's display name or GUID|

## <a name="BKMK_examples"></a>Examples
The following example gets the custom headers for the job named *myDownloadJob*.

```
C:\>bitsadmin /GetCustomHeaders myDownloadJob
```

## additional references
[Command-Line Syntax Key](command-line-syntax-key.md)


