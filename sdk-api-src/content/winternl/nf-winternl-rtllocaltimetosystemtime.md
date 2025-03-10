---
UID: NF:winternl.RtlLocalTimeToSystemTime
title: RtlLocalTimeToSystemTime function (winternl.h)
description: Converts the specified local time to system time.
old-location: base\rtllocaltimetosystemtime.htm
tech.root: SysInfo
ms.assetid: ce6f0578-0ea1-4e31-98a7-0008795abd32
ms.date: 12/05/2018
ms.keywords: RtlLocalTimeToSystemTime, RtlLocalTimeToSystemTime function, base.rtllocaltimetosystemtime, winternl/RtlLocalTimeToSystemTime
ms.topic: function
f1_keywords:
- winternl/RtlLocalTimeToSystemTime
dev_langs:
- c++
req.header: winternl.h
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
req.dll: Ntdll.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Ntdll.dll
api_name:
- RtlLocalTimeToSystemTime
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RtlLocalTimeToSystemTime function


## -description


<p class="CCE_Message">[<b>RtlLocalTimeToSystemTime</b> is available for use in Windows 2000 and Windows XP. It may be unavailable or modifed in subsequent releases. Applications should use the <a href="https://docs.microsoft.com/windows/desktop/api/fileapi/nf-fileapi-localfiletimetofiletime">LocalFileTimeToFileTime</a> function.]

Converts the specified local time to system time.


## -parameters




### -param LocalTime [in]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/winnt/ns-winnt-large_integer~r1">LARGE_INTEGER</a> structure that specifies the local time.


### -param SystemTime [out]

A pointer to a <a href="https://docs.microsoft.com/windows/win32/api/winnt/ns-winnt-large_integer~r1">LARGE_INTEGER</a> structure that receives the returned system time.


## -returns



If the function succeeds, it returns STATUS_SUCCESS.  If it fails, it will return the appropriate status code.




## -remarks



This function has no associated import library. You must use the <a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-loadlibrarya">LoadLibrary</a> and <a href="https://docs.microsoft.com/windows/desktop/api/libloaderapi/nf-libloaderapi-getprocaddress">GetProcAddress</a> functions to dynamically link to Ntdll.dll.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/fileapi/nf-fileapi-localfiletimetofiletime">LocalFileTimeToFileTime</a>



<a href="https://docs.microsoft.com/windows/desktop/SysInfo/time-functions">Time Functions</a>
 

 

