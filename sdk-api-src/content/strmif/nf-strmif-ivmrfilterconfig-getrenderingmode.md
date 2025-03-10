---
UID: NF:strmif.IVMRFilterConfig.GetRenderingMode
title: IVMRFilterConfig::GetRenderingMode (strmif.h)
description: The GetRenderingMode method retrieves the rendering mode currently being used by the VMR.
old-location: dshow\ivmrfilterconfig_getrenderingmode.htm
tech.root: DirectShow
ms.assetid: 139b0326-2ab1-4fa4-91ae-9115b4368660
ms.date: 12/05/2018
ms.keywords: GetRenderingMode, GetRenderingMode method [DirectShow], GetRenderingMode method [DirectShow],IVMRFilterConfig interface, IVMRFilterConfig interface [DirectShow],GetRenderingMode method, IVMRFilterConfig.GetRenderingMode, IVMRFilterConfig::GetRenderingMode, IVMRFilterConfigGetRenderingMode, dshow.ivmrfilterconfig_getrenderingmode, strmif/IVMRFilterConfig::GetRenderingMode
ms.topic: method
f1_keywords:
- strmif/IVMRFilterConfig.GetRenderingMode
dev_langs:
- c++
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP1 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Strmiids.lib
- Strmiids.dll
api_name:
- IVMRFilterConfig.GetRenderingMode
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IVMRFilterConfig::GetRenderingMode


## -description



The <code>GetRenderingMode</code> method retrieves the rendering mode currently being used by the VMR.




## -parameters




### -param pMode [out]

Pointer to a <b>DWORD</b> that receives a <a href="https://docs.microsoft.com/windows/desktop/api/strmif/ne-strmif-vmrmode">VMRMode</a> value indicating the current rendering mode.


## -returns



If the method succeeds, it returns S_OK. If it fails, it returns an error code.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
<i>pMode</i> is invalid

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nn-strmif-ivmrfilterconfig">IVMRFilterConfig Interface</a>



<a href="https://docs.microsoft.com/windows/desktop/api/strmif/nf-strmif-ivmrfilterconfig-setrenderingmode">IVMRFilterConfig::SetRenderingMode</a>



<a href="https://docs.microsoft.com/windows/desktop/DirectShow/using-the-video-mixing-renderer">Using the Video Mixing Renderer</a>
 

 

