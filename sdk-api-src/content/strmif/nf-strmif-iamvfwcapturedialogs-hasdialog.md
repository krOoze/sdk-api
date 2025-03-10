---
UID: NF:strmif.IAMVfwCaptureDialogs.HasDialog
title: IAMVfwCaptureDialogs::HasDialog (strmif.h)
description: The HasDialog method determines if the specified dialog box exists in the driver.
old-location: dshow\iamvfwcapturedialogs_hasdialog.htm
tech.root: DirectShow
ms.assetid: be2d9b1f-c53f-4a75-89ab-ec07c655cbea
ms.date: 12/05/2018
ms.keywords: HasDialog, HasDialog method [DirectShow], HasDialog method [DirectShow],IAMVfwCaptureDialogs interface, IAMVfwCaptureDialogs interface [DirectShow],HasDialog method, IAMVfwCaptureDialogs.HasDialog, IAMVfwCaptureDialogs::HasDialog, IAMVfwCaptureDialogsHasDialog, dshow.iamvfwcapturedialogs_hasdialog, strmif/IAMVfwCaptureDialogs::HasDialog
ms.topic: method
f1_keywords:
- strmif/IAMVfwCaptureDialogs.HasDialog
dev_langs:
- c++
req.header: strmif.h
req.include-header: Dshow.h
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
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IAMVfwCaptureDialogs.HasDialog
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IAMVfwCaptureDialogs::HasDialog


## -description



The <code>HasDialog</code> method determines if the specified dialog box exists in the driver.




## -parameters




### -param iDialog [in]

Desired dialog box. This is a member of the <a href="https://docs.microsoft.com/windows/desktop/api/strmif/ne-strmif-vfwcapturedialogs">VfwCaptureDialogs</a> enumeration.


## -returns



Returns S_OK if the driver contains the dialog box or S_FALSE otherwise.




## -remarks



This method calls the Video for Windows <b>videoDialog</b> function to query for the existence of the appropriate dialog box.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nn-strmif-iamvfwcapturedialogs">IAMVfwCaptureDialogs Interface</a>
 

 

