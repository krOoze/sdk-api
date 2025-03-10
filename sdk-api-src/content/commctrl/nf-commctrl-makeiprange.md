---
UID: NF:commctrl.MAKEIPRANGE
title: MAKEIPRANGE macro (commctrl.h)
description: Packs two byte-values into a single LPARAM suitable for use with the IPM_SETRANGE message.
old-location: controls\MAKEIPRANGE.htm
tech.root: Controls
ms.assetid: VS|Controls|~\controls\ipaddress\macros\makeiprange.htm
ms.date: 12/05/2018
ms.keywords: MAKEIPRANGE, MAKEIPRANGE macro [Windows Controls], _win32_MAKEIPRANGE, _win32_MAKEIPRANGE_cpp, commctrl/MAKEIPRANGE, controls.MAKEIPRANGE, controls._win32_MAKEIPRANGE
ms.topic: macro
f1_keywords:
- commctrl/MAKEIPRANGE
dev_langs:
- c++
req.header: commctrl.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- Commctrl.h
api_name:
- MAKEIPRANGE
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# MAKEIPRANGE macro


## -description


Packs two byte-values into a single LPARAM suitable for use with the <a href="https://docs.microsoft.com/windows/desktop/Controls/ipm-setrange">IPM_SETRANGE</a> message. 


## -parameters




### -param low

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">BYTE</a></b>

The lower limit of the range. 


### -param high

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">BYTE</a></b>

The upper limit of the range. 

