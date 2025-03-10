---
UID: NF:shlobj_core.SHChangeNotification_Unlock
title: SHChangeNotification_Unlock function (shlobj_core.h)
description: Unlocks shared memory for a change notification.
old-location: shell\SHChangeNotification_Unlock.htm
tech.root: shell
ms.assetid: 967ede1f-ee9c-46ee-a371-dcfc3a57d824
ms.date: 12/05/2018
ms.keywords: SHChangeNotification_Unlock, SHChangeNotification_Unlock function [Windows Shell], _win32_SHChangeNotification_Unlock, shell.SHChangeNotification_Unlock, shlobj_core/SHChangeNotification_Unlock
ms.topic: function
f1_keywords:
- shlobj_core/SHChangeNotification_Unlock
dev_langs:
- c++
req.header: shlobj_core.h
req.include-header: Shlobj.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Shell32.lib
req.dll: Shell32.dll (version 6.0 or later)
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Shell32.dll
- ext-ms-win-shell-shell32-l1-2-1.dll
- Ext-MS-Win-Shell-Shell32-L1-2-2.dll
api_name:
- SHChangeNotification_Unlock
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# SHChangeNotification_Unlock function


## -description


Unlocks shared memory for a change notification.


## -parameters




### -param hLock [in]

Type: <b>HANDLE</b>

A handle to the memory lock. This is the handle returned by <a href="https://docs.microsoft.com/windows/desktop/api/shlobj_core/nf-shlobj_core-shchangenotification_lock">SHChangeNotification_Lock</a> when it locked the memory.


## -returns



Type: <b>BOOL</b>

Returns <b>TRUE</b> on success; otherwise, <b>FALSE</b>.



