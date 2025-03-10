---
UID: NF:mfmediaengine.IMFMediaEngineEx.RemoveAllEffects
title: IMFMediaEngineEx::RemoveAllEffects (mfmediaengine.h)
description: Removes all audio and video effects.
old-location: mf\imfmediaengineex_removealleffects.htm
tech.root: medfound
ms.assetid: B9EF1440-27DA-48C6-B840-FF61DBF19E63
ms.date: 12/05/2018
ms.keywords: IMFMediaEngineEx interface [Media Foundation],RemoveAllEffects method, IMFMediaEngineEx.RemoveAllEffects, IMFMediaEngineEx::RemoveAllEffects, RemoveAllEffects, RemoveAllEffects method [Media Foundation], RemoveAllEffects method [Media Foundation],IMFMediaEngineEx interface, mf.imfmediaengineex_removealleffects, mfmediaengine/IMFMediaEngineEx::RemoveAllEffects
ms.topic: method
f1_keywords:
- mfmediaengine/IMFMediaEngineEx.RemoveAllEffects
dev_langs:
- c++
req.header: mfmediaengine.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2012 [desktop apps \| UWP apps]
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
- mfmediaengine.h
api_name:
- IMFMediaEngineEx.RemoveAllEffects
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IMFMediaEngineEx::RemoveAllEffects


## -description


Removes all audio and video effects.


## -parameters






## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



 Call this method to remove all of the effects that were added with the <a href="https://docs.microsoft.com/windows/desktop/api/mfmediaengine/nf-mfmediaengine-imfmediaengineex-insertaudioeffect">InsertAudioEffect</a> and <a href="https://docs.microsoft.com/windows/desktop/api/mfmediaengine/nf-mfmediaengine-imfmediaengineex-insertvideoeffect">InsertVideoEffect</a> methods.






## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mfmediaengine/nn-mfmediaengine-imfmediaengineex">IMFMediaEngineEx</a>
 

 

