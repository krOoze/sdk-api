---
UID: NF:drt.DrtGetSearchResult
title: DrtGetSearchResult function (drt.h)
description: DrtGetSearchResult function.
old-location: p2p\drtgetsearchresult.htm
tech.root: P2PSdk
ms.assetid: b89ea470-072e-46b6-9f5d-3e05aa012188
ms.date: 12/05/2018
ms.keywords: DrtGetSearchResult, DrtGetSearchResult function [Peer Networking], drt/DrtGetSearchResult, p2p.drtgetsearchresult
ms.topic: function
f1_keywords:
- drt/DrtGetSearchResult
dev_langs:
- c++
req.header: drt.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 Professional [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Drt.lib
req.dll: Drt.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- drt.dll
api_name:
- DrtGetSearchResult
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# DrtGetSearchResult function


## -description


The <b>DrtGetSearchResult</b> function allows the caller to retrieve the search result(s).


## -parameters




### -param hSearchContext [in]

Handle to the search context to close. This parameter is returned by the <a href="https://docs.microsoft.com/windows/desktop/api/drt/nf-drt-drtstartsearch">DrtStartSearch</a> function.


### -param ulSearchResultSize [out]

Pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/drt/ns-drt-drt_search_result">DRT_SEARCH_RESULT</a> structure containing the search result.


### -param pSearchResult

Receives a pointer to a DRT_SEARCH_RESULT structure containing the search results.




## -returns



This function returns S_OK on success. Other possible values include:

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
<i>ulSearchPathSize</i>  is less than the  size of <a href="https://docs.microsoft.com/windows/desktop/api/drt/ns-drt-drt_search_result">DRT_SEARCH_RESULT</a>.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_HANDLE</b></dt>
</dl>
</td>
<td width="60%">
<i>hSearchContext</i> is an invalid handle.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>DRT_E_FAULTED</b></dt>
</dl>
</td>
<td width="60%">
the DRT cloud is in the faulted state.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>DRT_E_INSUFFICIENT_BUFFER</b></dt>
</dl>
</td>
<td width="60%">
The provided buffer is insufficient in size to contain the search result.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>DRT_E_NO_MORE</b></dt>
</dl>
</td>
<td width="60%">
There are no more results to return.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>DRT_E_TIMEOUT</b></dt>
</dl>
</td>
<td width="60%">
  The search failed because it timed out.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>DRT_E_SEARCH_IN_PROGRESS</b></dt>
</dl>
</td>
<td width="60%">
The search is currently in progress.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/drt/nf-drt-drtstartsearch">DrtStartSearch</a>
 

 

