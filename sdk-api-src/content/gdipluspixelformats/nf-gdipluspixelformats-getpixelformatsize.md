---
UID: NF:gdipluspixelformats.GetPixelFormatSize
title: GetPixelFormatSize function (gdipluspixelformats.h)
description: The GetPixelFormatSize method returns the number of bits per pixel used by a specified pixel format.
old-location: gdiplus\_gdiplus_FUNC_GetPixelFormatSize_.htm
tech.root: gdiplus
ms.assetid: VS|gdicpp|~\gdiplus\gdiplusreference\functions\getpixelformatsize.htm
ms.date: 12/05/2018
ms.keywords: GetPixelFormatSize, GetPixelFormatSize function [GDI+], _gdiplus_FUNC_GetPixelFormatSize_, gdiplus._gdiplus_FUNC_GetPixelFormatSize_, gdipluspixelformats/GetPixelFormatSize
ms.topic: function
f1_keywords:
- gdipluspixelformats/GetPixelFormatSize
dev_langs:
- c++
req.header: gdipluspixelformats.h
req.include-header: Gdiplus.h
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Gdiplus.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- LibDef
api_location:
- Gdiplus.lib
- Gdiplus.dll
api_name:
- GetPixelFormatSize
targetos: Windows
req.typenames: 
req.redist: 
req.product: GDI+ 1.1
ms.custom: 19H1
---

# GetPixelFormatSize function


## -description


The <b>GetPixelFormatSize</b> method returns the number of bits per pixel used by a specified pixel format.


## -parameters




### -param pixfmt

Type: <b>PixelFormat</b>

A <a href="https://docs.microsoft.com/windows/desktop/gdiplus/-gdiplus-constant-image-pixel-format-constants">PixelFormat</a> constant that specifies the pixel format to be tested.


## -returns



Type: <strong>Type: <b>UINT</b>
</strong>

This method returns the number of bits per pixel used by the specified pixel format.



