---
UID: NF:tapi.phoneConfigDialogW
title: phoneConfigDialogW function (tapi.h)
description: The phoneConfigDialog function causes the provider of the specified phone device to display a modal dialog box that allows the user to configure parameters related to the phone device.
old-location: tapi2\phoneconfigdialog.htm
tech.root: Tapi
ms.assetid: 64f2626a-283d-47c8-aecd-57d31712a700
ms.date: 12/05/2018
ms.keywords: _tapi2_phoneconfigdialog, phoneConfigDialog, phoneConfigDialog function [TAPI 2.2], phoneConfigDialogA, phoneConfigDialogW, tapi/phoneConfigDialog, tapi/phoneConfigDialogA, tapi/phoneConfigDialogW, tapi2.phoneconfigdialog
ms.topic: function
f1_keywords:
- tapi/phoneConfigDialog
dev_langs:
- c++
req.header: tapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: phoneConfigDialogW (Unicode) and phoneConfigDialogA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Tapi32.lib
req.dll: Tapi32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Tapi32.dll
api_name:
- phoneConfigDialog
- phoneConfigDialogA
- phoneConfigDialogW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# phoneConfigDialogW function


## -description


The 
<b>phoneConfigDialog</b> function causes the provider of the specified phone device to display a modal dialog box (attached to the application's <i>hwndOwner</i> parameter) that allows the user to configure parameters related to the phone device specified by <i>dwDeviceID</i>.


## -parameters




### -param dwDeviceID

Identifier of the phone device to be configured.


### -param hwndOwner

Handle to a window to which the dialog box is to be attached. Can be a <b>NULL</b> value to indicate that any window created during the function should have no owner window.


### -param lpszDeviceClass

Pointer to a <b>null</b>-terminated string that identifies a device class name. This device class allows the application to select a specific subscreen of configuration information applicable to that device class. This parameter is optional and can be left <b>NULL</b> or empty, in which case the highest level configuration is selected.


## -returns



Returns zero if the request succeeds or a negative error number if an error occurs. Possible return values are:

PHONEERR_BADDEVICEID, PHONEERR_NOMEM, PHONEERR_INUSE, PHONEERR_OPERATIONFAILED, PHONEERR_INVALPARAM, PHONEERR_OPERATIONUNAVAIL, PHONEERR_INVALDEVICECLASS, PHONEERR_RESOURCEUNAVAIL, PHONEERR_INVALPOINTER, PHONEERR_UNINITIALIZED, PHONEERR_NODEVICE.




## -remarks



The <i>lpszDeviceClass</i> parameter allows the application to select a specific subscreen of configuration information applicable to the device class in which the user is interested; the permitted strings are the same as for 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi/nf-tapi-phonegetid">phoneGetID</a>. For example, if the phone supports the wave API, passing "wave/in" as <i>lpszDeviceClass</i> would cause the provider to display the parameters related specifically to wave (or at least to start at the corresponding point in a multilevel configuration dialog box chain, eliminating the need to search for relevant parameters).

The <i>lpszDeviceClass</i> parameter should be "tapi/phone", "", or <b>NULL</b> to cause the provider to display the highest level configuration for the phone.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/Tapi/supplementary-phone-service-functions">Supplementary Phone Service Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/Tapi/tapi-2-2-reference">TAPI 2.2 Reference Overview</a>



<a href="https://docs.microsoft.com/windows/desktop/api/tapi/nf-tapi-phonegetid">phoneGetID</a>
 

 

