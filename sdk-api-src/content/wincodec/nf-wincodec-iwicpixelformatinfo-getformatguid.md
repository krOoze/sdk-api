---
UID: NF:wincodec.IWICPixelFormatInfo.GetFormatGUID
title: IWICPixelFormatInfo::GetFormatGUID (wincodec.h)
description: Gets the pixel format GUID.
old-location: wic\_wic_codec_iwicpixelformatinfo_getformatguid.htm
tech.root: wic
ms.assetid: 184ad8e5-51f2-47eb-b3c4-010626fa7c34
ms.date: 12/05/2018
ms.keywords: GetFormatGUID, GetFormatGUID method [Windows Imaging Component], GetFormatGUID method [Windows Imaging Component],IWICPixelFormatInfo interface, IWICPixelFormatInfo interface [Windows Imaging Component],GetFormatGUID method, IWICPixelFormatInfo.GetFormatGUID, IWICPixelFormatInfo::GetFormatGUID, _wic_codec_iwicpixelformatinfo_getformatguid, wic._wic_codec_iwicpixelformatinfo_getformatguid, wincodec/IWICPixelFormatInfo::GetFormatGUID
ms.topic: method
f1_keywords:
- wincodec/IWICPixelFormatInfo.GetFormatGUID
dev_langs:
- c++
req.header: wincodec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Wincodec.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Windowscodecs.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Windowscodecs.lib
- Windowscodecs.dll
api_name:
- IWICPixelFormatInfo.GetFormatGUID
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWICPixelFormatInfo::GetFormatGUID


## -description


Gets the pixel format GUID.


## -parameters




### -param pFormat [out]

Type: <b>GUID*</b>

Pointer that receives the pixel format GUID.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



