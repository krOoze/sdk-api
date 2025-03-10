---
UID: NF:amstream.IAMMediaTypeStream.GetFormat
title: IAMMediaTypeStream::GetFormat (amstream.h)
description: Note  This interface is deprecated. New applications should not use it. The GetFormat method retrieves the format of the stream.
old-location: dshow\iammediatypestream_getformat.htm
tech.root: DirectShow
ms.assetid: 9f00fe45-df4b-4787-980c-9fe434a8ab7e
ms.date: 12/05/2018
ms.keywords: GetFormat, GetFormat method [DirectShow], GetFormat method [DirectShow],IAMMediaTypeStream interface, IAMMediaTypeStream interface [DirectShow],GetFormat method, IAMMediaTypeStream.GetFormat, IAMMediaTypeStream::GetFormat, IAMMediaTypeStreamGetFormat, amstream/IAMMediaTypeStream::GetFormat, dshow.iammediatypestream_getformat
ms.topic: method
f1_keywords:
- amstream/IAMMediaTypeStream.GetFormat
dev_langs:
- c++
req.header: amstream.h
req.include-header: 
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
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- amstream.h
api_name:
- IAMMediaTypeStream.GetFormat
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IAMMediaTypeStream::GetFormat


## -description



<div class="alert"><b>Note</b>  This interface is deprecated. New applications should not use it.</div>
<div> </div>
The <code>GetFormat</code> method retrieves the format of the stream.




## -parameters




### -param pMediaType [out]

Pointer to an <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/strmif/ns-strmif-am_media_type">AM_MEDIA_TYPE</a> structure that receives the stream format.


### -param dwFlags [in]

Reserved.


## -returns



Returns one of the following values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>MS_E_NOSTREAM</b></dt>
</dl>
</td>
<td width="60%">
No stream is associated with this object.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/amstream/nn-amstream-iammediatypestream">IAMMediaTypeStream Interface</a>
 

 

