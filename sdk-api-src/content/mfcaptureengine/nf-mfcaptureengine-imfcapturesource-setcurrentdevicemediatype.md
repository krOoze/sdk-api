---
UID: NF:mfcaptureengine.IMFCaptureSource.SetCurrentDeviceMediaType
title: IMFCaptureSource::SetCurrentDeviceMediaType (mfcaptureengine.h)
description: Sets the output format for a capture stream.
old-location: mf\imfcapturesource_setcurrentdevicemediatype.htm
tech.root: medfound
ms.assetid: 2B88BBAE-E837-4F4A-B697-64772F25C89D
ms.date: 12/05/2018
ms.keywords: IMFCaptureSource interface [Media Foundation],SetCurrentDeviceMediaType method, IMFCaptureSource.SetCurrentDeviceMediaType, IMFCaptureSource::SetCurrentDeviceMediaType, MF_CAPTURE_ENGINE_FIRST_SOURCE_AUDIO_STREAM, MF_CAPTURE_ENGINE_FIRST_SOURCE_PHOTO_STREAM, MF_CAPTURE_ENGINE_FIRST_SOURCE_VIDEO_STREAM, SetCurrentDeviceMediaType, SetCurrentDeviceMediaType method [Media Foundation], SetCurrentDeviceMediaType method [Media Foundation],IMFCaptureSource interface, mf.imfcapturesource_setcurrentdevicemediatype, mfcaptureengine/IMFCaptureSource::SetCurrentDeviceMediaType
ms.topic: method
f1_keywords:
- mfcaptureengine/IMFCaptureSource.SetCurrentDeviceMediaType
dev_langs:
- c++
req.header: mfcaptureengine.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps only]
req.target-min-winversvr: Windows Server 2012 [desktop apps only]
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
- mfcaptureengine.h
api_name:
- IMFCaptureSource.SetCurrentDeviceMediaType
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMFCaptureSource::SetCurrentDeviceMediaType


## -description


Sets the output format for a capture stream.


## -parameters




### -param dwSourceStreamIndex [in]

The capture stream to set. The value can be any of the following.

<table>
<tr>
<th>Value</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt>0–0xFFFFFFFB</dt>
</dl>
</td>
<td width="60%">
The zero-based index of a stream. To get the number of streams, call <a href="https://docs.microsoft.com/windows/desktop/api/mfcaptureengine/nf-mfcaptureengine-imfcapturesource-getdevicestreamcount">IMFCaptureSource::GetDeviceStreamCount</a>.

</td>
</tr>
<tr>
<td width="40%"><a id="MF_CAPTURE_ENGINE_FIRST_SOURCE_PHOTO_STREAM"></a><a id="mf_capture_engine_first_source_photo_stream"></a><dl>
<dt><b><b>MF_CAPTURE_ENGINE_FIRST_SOURCE_PHOTO_STREAM</b></b></dt>
<dt>0xFFFFFFFB</dt>
</dl>
</td>
<td width="60%">
The first image stream.

</td>
</tr>
<tr>
<td width="40%"><a id="MF_CAPTURE_ENGINE_FIRST_SOURCE_VIDEO_STREAM"></a><a id="mf_capture_engine_first_source_video_stream"></a><dl>
<dt><b><b>MF_CAPTURE_ENGINE_FIRST_SOURCE_VIDEO_STREAM</b></b></dt>
<dt>0xFFFFFFFC</dt>
</dl>
</td>
<td width="60%">
The first video stream.

</td>
</tr>
<tr>
<td width="40%"><a id="MF_CAPTURE_ENGINE_FIRST_SOURCE_AUDIO_STREAM"></a><a id="mf_capture_engine_first_source_audio_stream"></a><dl>
<dt><b><b>MF_CAPTURE_ENGINE_FIRST_SOURCE_AUDIO_STREAM</b></b></dt>
<dt>0xFFFFFFFD</dt>
</dl>
</td>
<td width="60%">
The first audio stream.

</td>
</tr>
</table>
 


### -param pMediaType [in]

A pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/mfobjects/nn-mfobjects-imfmediatype">IMFMediaType</a> interface.


## -returns



This method can return one of these values.

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
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>MF_E_INVALIDSTREAMNUMBER</b></dt>
</dl>
</td>
<td width="60%">
The <i>dwSourceStreamIndex</i> parameter is invalid.

</td>
</tr>
</table>
 




## -remarks



This method sets the native output type on the capture device. The device must support the specified format. To get the list of available formats, call <a href="https://docs.microsoft.com/windows/desktop/api/mfcaptureengine/nf-mfcaptureengine-imfcapturesource-getavailabledevicemediatype">IMFCaptureSource::GetAvailableDeviceMediaType</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mfcaptureengine/nn-mfcaptureengine-imfcapturesource">IMFCaptureSource</a>
 

 

