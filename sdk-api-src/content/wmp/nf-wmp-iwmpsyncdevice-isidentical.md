---
UID: NF:wmp.IWMPSyncDevice.isIdentical
title: IWMPSyncDevice::isIdentical (wmp.h)
description: The isIdentical method compares the current device to the specified device and retrieves a value indicating whether they are the same device.
old-location: wmp\iwmpsyncdevice_isidentical.htm
tech.root: WMP
ms.assetid: 4335d480-5af0-4764-b8f8-0e6edc1598b7
ms.date: 12/05/2018
ms.keywords: IWMPSyncDevice interface [Windows Media Player],isIdentical method, IWMPSyncDevice.isIdentical, IWMPSyncDevice::isIdentical, IWMPSyncDeviceisIdentical, isIdentical, isIdentical method [Windows Media Player], isIdentical method [Windows Media Player],IWMPSyncDevice interface, wmp.iwmpsyncdevice_isidentical, wmp/IWMPSyncDevice::isIdentical
ms.topic: method
f1_keywords:
- wmp/IWMPSyncDevice.isIdentical
dev_langs:
- c++
req.header: wmp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Media Player 10 or later.
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
req.lib: 
req.dll: Wmp.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- wmp.dll
api_name:
- IWMPSyncDevice.isIdentical
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IWMPSyncDevice::isIdentical


## -description



The <b>isIdentical</b> method compares the current device to the specified device and retrieves a value indicating whether they are the same device.




## -parameters




### -param pDevice [in]

Pointer to an <b>IWMPSyncDevice</b> interface that represents the device to which to compare the current device.


### -param pvbool [out]

Pointer to a <b>VARIANT_BOOL</b> that indicates the result of the comparison.


## -returns



The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>NS_E_PDA_INITIALIZINGDEVICES (0xC00D118D)</b></dt>
</dl>
</td>
<td width="60%">
Windows Media Player is currently busy initializing devices. Please try again later.

</td>
</tr>
</table>
 




## -remarks



This method is useful in event handlers that provide an <b>IWMPSyncDevice</b> pointer as a parameter.

<b>Windows Media Player 10 Mobile: </b>This method is not supported.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/wmp/nn-wmp-iwmpsyncdevice">IWMPSyncDevice Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/WMP/showing-synchronization-progress">Showing Synchronization Progress</a>
 

 

