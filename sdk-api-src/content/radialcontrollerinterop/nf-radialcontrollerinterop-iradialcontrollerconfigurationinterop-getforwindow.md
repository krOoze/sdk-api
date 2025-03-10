---
UID: NF:radialcontrollerinterop.IRadialControllerConfigurationInterop.GetForWindow
title: IRadialControllerConfigurationInterop::GetForWindow (radialcontrollerinterop.h)
description: Retrieves a RadialControllerConfiguration object bound to the active application.
old-location: input_radial\iradialcontrollerconfigurationinterop_getforwindow.htm
tech.root: Input_Radial
ms.assetid: f2182f3a-82a8-40be-b331-673a181f4070
ms.date: 12/05/2018
ms.keywords: GetForWindow, GetForWindow method, GetForWindow method,IRadialControllerConfigurationInterop interface, IRadialControllerConfigurationInterop interface,GetForWindow method, IRadialControllerConfigurationInterop.GetForWindow, IRadialControllerConfigurationInterop::GetForWindow, Input_Radial.iradialcontrollerconfigurationinterop_getforwindow, radialcontrollerinterop/IRadialControllerConfigurationInterop::GetForWindow
ms.topic: method
f1_keywords:
- radialcontrollerinterop/IRadialControllerConfigurationInterop.GetForWindow
dev_langs:
- c++
req.header: radialcontrollerinterop.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1607 [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: RadialControllerInterop.idl
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
- COM
api_location:
- RadialControllerInterop.h
api_name:
- IRadialControllerConfigurationInterop.GetForWindow
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IRadialControllerConfigurationInterop::GetForWindow


## -description


Retrieves a <a href="https://docs.microsoft.com/en-us/uwp/api/windows.ui.input.radialcontrollerconfiguration">RadialControllerConfiguration</a> object bound to the active application.


## -parameters




### -param hwnd [in]

Handle to the window of the active application.


### -param riid [in]

The GUID of the <a href="https://docs.microsoft.com/en-us/uwp/api/windows.ui.input.radialcontrollerconfiguration">RadialControllerConfiguration</a> object.


### -param ppv [out]

Address of a pointer to a <a href="https://docs.microsoft.com/en-us/uwp/api/windows.ui.input.radialcontrollerconfiguration">RadialControllerConfiguration</a> object.


## -returns



If this function succeeds, it returns <b>S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.




## -see-also




<b>Developer and UX guidance</b>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/radialcontrollerinterop/nn-radialcontrollerinterop-iradialcontrollerconfigurationinterop">IRadialControllerConfigurationInterop</a>



<b>Samples</b>



<a href="https://go.microsoft.com/fwlink/?linkid=832322">Surface Dial interactions</a>



<a href="https://go.microsoft.com/fwlink/?linkid=832713">Universal Windows Platform samples (C# and C++)</a>



<a href="https://aka.ms/radialcontrollerclassicsample">Windows classic desktop sample</a>
 

 

