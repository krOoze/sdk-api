---
UID: NF:dvbsiparser.IIsdbEventGroupDescriptor.GetGroupType
title: IIsdbEventGroupDescriptor::GetGroupType (dvbsiparser.h)
description: Gets a code that describes the event group type from an Integrated Services Digital Broadcasting (ISDB) event group descriptor.
old-location: mstv\iisdbeventgroupdescriptor_getgrouptype.htm
tech.root: mstv
ms.assetid: 152bae4a-f4e6-4e9e-a1ed-19240cf8108c
ms.date: 12/05/2018
ms.keywords: GetGroupType, GetGroupType method [Microsoft TV Technologies], GetGroupType method [Microsoft TV Technologies],IIsdbEventGroupDescriptor interface, IIsdbEventGroupDescriptor interface [Microsoft TV Technologies],GetGroupType method, IIsdbEventGroupDescriptor.GetGroupType, IIsdbEventGroupDescriptor::GetGroupType, dvbsiparser/IIsdbEventGroupDescriptor::GetGroupType, mstv.iisdbeventgroupdescriptor_getgrouptype
ms.topic: method
f1_keywords:
- dvbsiparser/IIsdbEventGroupDescriptor.GetGroupType
dev_langs:
- c++
req.header: dvbsiparser.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Dvbsiparser.idl
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
- dvbsiparser.h
api_name:
- IIsdbEventGroupDescriptor.GetGroupType
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IIsdbEventGroupDescriptor::GetGroupType


## -description


 Gets a code that describes the event group type from an Integrated Services Digital Broadcasting (ISDB) event group descriptor.


## -parameters




### -param pbVal [out]

Receives the event group type. This can be any of the following values.

<table>
<tr>
<th>Value</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x1</dt>
</dl>
</td>
<td width="60%">
Event common.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x2</dt>
</dl>
</td>
<td width="60%">
Event relay.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x3</dt>
</dl>
</td>
<td width="60%">
Event movement.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x4</dt>
</dl>
</td>
<td width="60%">
Event relay to other networks.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x5</dt>
</dl>
</td>
<td width="60%">
Event movement from other networks.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0x0, 0x6-0xF</dt>
</dl>
</td>
<td width="60%">
Undefined.

</td>
</tr>
</table>
 


## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-iisdbeventgroupdescriptor">IIsdbEventGroupDescriptor</a>
 

 

