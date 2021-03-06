---
title: bitsadmin getnotifyinterface
description: Windows Commands topic for **bitsadmin getnotifyinterface**, which determines if another program has registered a COM callback interface for the specified job.
ms.prod: windows-server
ms.technology: manage-windows-commands
ms.topic: article
ms.assetid: 40bf9dd8-b167-406a-80a6-a5a6f1b8cf7f
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# bitsadmin getnotifyinterface

Determines whether another program has registered a COM callback interface (the notify interface) for the specified job.

## Syntax

```
bitsadmin /getnotifyinterface <job>
```

### Parameters

| Parameter | Description |
| -------------- | -------------- |
| job | The job's display name or GUID. |

#### Output

The output for this command displays either, **Registered** or **Unregistered**.

> [!NOTE]
> It is not possible to determine the program that registered the callback interface.

## <a name=BKMK_examples></a>Examples

The following example retrieves the notify interface for the job named *myDownloadJob*.

```
C:\>bitsadmin /getnotifyinterface myDownloadJob
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)