---
title: bitsadmin suspend
description: Windows Commands topic for **bitsadmin suspend**, which suspends the specified job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: f9d42500-7bea-4aa8-a9f0-c22f6ed3e73b
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---
# bitsadmin suspend

> Applies To: Windows Server (Semi-Annual Channel), Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Suspends the specified job. If you suspended your job by mistake, you can use the [bitsadmin resume](bitsadmin-resume.md) switch to restart the job.

## Syntax

```
bitsadmin /suspend <job>
```

### Parameters

| Parameter | Description |
| --------- | ---------- |
| Job | The job's display name or GUID. |

## Example

The following example suspends the job named *myDownloadJob*.


```
C:\>bitsadmin /suspend myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)
