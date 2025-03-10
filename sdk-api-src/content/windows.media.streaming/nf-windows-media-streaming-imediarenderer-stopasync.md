---
UID: NF:windows.media.streaming.IMediaRenderer.StopAsync
title: IMediaRenderer::streaming (windows.media.streaming.h)
description: Instructs the DMR asynchronously to stop playing the current content.
old-location: mediastreaming\imediarenderer_stopasync.htm
tech.root: mediastreaming
ms.assetid: B6B0F3F2-E95E-4A58-9CBD-CF4CB24FDAD0
ms.date: 12/05/2018
ms.keywords: IMediaRenderer interface [Media Streaming API],StopAsync method, IMediaRenderer.StopAsync, IMediaRenderer.streaming, IMediaRenderer::StopAsync, IMediaRenderer::streaming, StopAsync, StopAsync method [Media Streaming API], StopAsync method [Media Streaming API],IMediaRenderer interface, mediastreaming.imediarenderer_stopasync, windows/IMediaRenderer::StopAsync
ms.topic: method
f1_keywords:
- windows.media.streaming/IMediaRenderer.StopAsync
dev_langs:
- c++
req.header: windows.media.streaming.h
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
- windows.media.streaming.h
api_name:
- IMediaRenderer.StopAsync
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMediaRenderer::streaming


## -description


Instructs the DMR asynchronously to stop playing the current content.


## -parameters




### -param value [out]

Receives a reference to a <a href="https://docs.microsoft.com/windows/desktop/mediastreaming/playbackoperation">PlaybackOperation</a> object that is used to get results from the asynchronous operation.


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
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/mediastreaming/imediarenderer">IMediaRenderer</a>
 

 

