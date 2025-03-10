---
UID: NF:tapi3if.ITPhone.SetDisplay
title: ITPhone::SetDisplay (tapi3if.h)
description: The SetDisplay method sets what will appear in a given row and column of the phone's display.
old-location: tapi3\itphone_setdisplay.htm
tech.root: Tapi
ms.assetid: 690756c4-201d-472d-b536-452074226701
ms.date: 12/05/2018
ms.keywords: ITPhone interface [TAPI 2.2],SetDisplay method, ITPhone.SetDisplay, ITPhone::SetDisplay, SetDisplay, SetDisplay method [TAPI 2.2], SetDisplay method [TAPI 2.2],ITPhone interface, _tapi3_itphone_setdisplay, tapi3.itphone_setdisplay, tapi3if/ITPhone::SetDisplay
ms.topic: method
f1_keywords:
- tapi3if/ITPhone.SetDisplay
dev_langs:
- c++
req.header: tapi3if.h
req.include-header: Tapi3.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Uuid.lib
req.dll: Tapi3.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Tapi3.dll
api_name:
- ITPhone.SetDisplay
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITPhone::SetDisplay


## -description


The 
<b>SetDisplay</b> method sets what will appear in a given row and column of the phone's display.


## -parameters




### -param lRow [in]

Display row.


### -param lColumn [in]

Display column.


### -param bstrDisplay [in]

The <b>BSTR</b> representation of the value to display.


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itphone">ITPhone</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nf-tapi3if-itphone-get_display">get_Display</a>
 

 

