---
UID: NF:wingdi.SetDeviceGammaRamp
title: SetDeviceGammaRamp function (wingdi.h)
description: The SetDeviceGammaRamp function sets the gamma ramp on direct color display boards having drivers that support downloadable gamma ramps in hardware.
old-location: wcs\setdevicegammaramp.htm
tech.root: WCS
ms.assetid: 8e4cc9a4-f292-47a1-a12a-43a479326ca7
ms.date: 12/05/2018
ms.keywords: SetDeviceGammaRamp, SetDeviceGammaRamp function [Windows Color System], _color_SetDeviceGammaRamp, wcs.setdevicegammaramp, wingdi/SetDeviceGammaRamp
ms.topic: function
f1_keywords:
- wingdi/SetDeviceGammaRamp
dev_langs:
- c++
req.header: wingdi.h
req.include-header: 
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
req.lib: Gdi32.lib
req.dll: Gdi32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- gdi32.dll
- Ext-MS-Win-GDI-wcs-l1-1-0.dll
- Ext-MS-Win-GDI-Internal-Desktop-L1-1-0.dll
- GDI32Full.dll
api_name:
- SetDeviceGammaRamp
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# SetDeviceGammaRamp function


## -description


The <b>SetDeviceGammaRamp</b> function sets the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/wcs/g">gamma ramp</a> on direct color display boards having drivers that support downloadable gamma ramps in hardware.


## -parameters




### -param hdc

Specifies the device context of the direct color display board in question.


### -param lpRamp

Pointer to a buffer containing the gamma ramp to be set. The gamma ramp is specified in three arrays of 256 <b>WORD</b> elements each, which contain the mapping between RGB values in the frame buffer and digital-analog-converter (<i>DAC</i> ) values. The sequence of the arrays is red, green, blue. The RGB values must be stored in the most significant bits of each WORD to increase DAC independence.


## -returns



If this function succeeds, the return value is <b>TRUE</b>.

If this function fails, the return value is <b>FALSE</b>.




## -remarks



Direct color display modes do not use color lookup tables and are usually 16, 24, or 32 bit. Not all direct color video boards support loadable gamma ramps. <b>SetDeviceGammaRamp</b> succeeds only for devices with drivers that support downloadable gamma ramps in hardware.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/wcs/basic-color-management-concepts">Basic Color Management Concepts</a>



<a href="https://docs.microsoft.com/previous-versions/dd316902(v=vs.85)">Functions</a>
 

 

