---
UID: NF:rtworkq.RtwqRegisterPlatformEvents
title: RtwqRegisterPlatformEvents function (rtworkq.h)
description: Enables an app to listen to the RtwqStartup and RtwqShutdown functions.
old-location: base\rtwqregisterplatformevents.htm
tech.root: ProcThread
ms.assetid: 7BD7E83B-29E1-4FF5-B527-71C2F80D6521
ms.date: 12/05/2018
ms.keywords: RtwqRegisterPlatformEvents, RtwqRegisterPlatformEvents function, base.rtwqregisterplatformevents, rtworkq/RtwqRegisterPlatformEvents
ms.topic: function
f1_keywords:
- rtworkq/RtwqRegisterPlatformEvents
dev_langs:
- c++
req.header: rtworkq.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8.1 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Rtworkq.lib
req.dll: RTWorkQ.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- RTWorkQ.dll
api_name:
- RtwqRegisterPlatformEvents
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RtwqRegisterPlatformEvents function

## -description

Enables an app to listen to the <a href="https://docs.microsoft.com/windows/desktop/api/rtworkq/nf-rtworkq-rtwqstartup">RtwqStartup</a> and <a href="https://docs.microsoft.com/windows/desktop/api/rtworkq/nf-rtworkq-rtwqshutdown">RtwqShutdown</a> functions.

## -parameters

### -param platformEvents [in]

Pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/rtworkq/nn-rtworkq-irtwqplatformevents">IRtwqPlatformEvents</a> object which provides the events.

## -returns

If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.
