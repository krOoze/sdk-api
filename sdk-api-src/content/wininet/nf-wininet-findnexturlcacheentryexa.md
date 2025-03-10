---
UID: NF:wininet.FindNextUrlCacheEntryExA
title: FindNextUrlCacheEntryExA function (wininet.h)
description: Finds the next cache entry in a cache enumeration started by the FindFirstUrlCacheEntryEx function.
old-location: wininet\findnexturlcacheentryex.htm
tech.root: wininet
ms.assetid: 39484e35-cd25-4e48-ace0-16033d3e6954
ms.date: 12/05/2018
ms.keywords: FindNextUrlCacheEntryEx, FindNextUrlCacheEntryEx function [WinINet], FindNextUrlCacheEntryExA, FindNextUrlCacheEntryExW, _inet_findnexturlcacheentryex_function, wininet.findnexturlcacheentryex, wininet/FindNextUrlCacheEntryEx, wininet/FindNextUrlCacheEntryExA, wininet/FindNextUrlCacheEntryExW
ms.topic: function
f1_keywords:
- wininet/FindNextUrlCacheEntryEx
dev_langs:
- c++
req.header: wininet.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: FindNextUrlCacheEntryExW (Unicode) and FindNextUrlCacheEntryExA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Wininet.lib
req.dll: Wininet.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Wininet.dll
api_name:
- FindNextUrlCacheEntryEx
- FindNextUrlCacheEntryExA
- FindNextUrlCacheEntryExW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# FindNextUrlCacheEntryExA function


## -description


Finds the next cache entry in a cache enumeration started by the 
<a href="https://docs.microsoft.com/windows/desktop/api/wininet/nf-wininet-findfirsturlcacheentryexa">FindFirstUrlCacheEntryEx</a> function.


## -parameters




### -param hEnumHandle [in]

Handle returned by 
<a href="https://docs.microsoft.com/windows/desktop/api/wininet/nf-wininet-findfirsturlcacheentryexa">FindFirstUrlCacheEntryEx</a>, which started a cache enumeration.


### -param lpNextCacheEntryInfo [in, out]

Pointer to the  
<a href="https://docs.microsoft.com/windows/desktop/api/wininet/ns-wininet-internet_cache_entry_infoa">INTERNET_CACHE_ENTRY_INFO</a> structure that receives the cache entry information.


### -param lpcbCacheEntryInfo [in, out]

Pointer to a variable that indicates the size of the buffer, in bytes.


### -param lpGroupAttributes

This parameter is reserved and must be <b>NULL</b>.


### -param lpcbGroupAttributes

This parameter is reserved and must be <b>NULL</b>.


### -param lpReserved

This parameter is reserved.


## -returns



Returns <b>TRUE</b> if successful, or <b>FALSE</b> otherwise. To get specific error information, call 
<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>.




## -remarks



Continue to call <b>FindNextUrlCacheEntryEx</b> until the last item in the cache is returned.

Like all other aspects of the WinINet API, this function cannot be safely called from within DllMain or the constructors and destructors of global objects.

<div class="alert"><b>Note</b>  WinINet does not support server implementations. In addition, it should not be used from a service.  For server implementations or services use <a href="https://docs.microsoft.com/windows/desktop/WinHttp/winhttp-start-page">Microsoft Windows HTTP Services (WinHTTP)</a>.</div>
<div> </div>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/WinInet/caching">Caching</a>



<a href="https://docs.microsoft.com/windows/desktop/WinInet/wininet-functions">WinINet Functions</a>
 

 

