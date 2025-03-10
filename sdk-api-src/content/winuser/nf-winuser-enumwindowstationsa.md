---
UID: NF:winuser.EnumWindowStationsA
title: EnumWindowStationsA function (winuser.h)
description: Enumerates all window stations in the current session. The function passes the name of each window station, in turn, to an application-defined callback function.
old-location: winstation\enumwindowstations.htm
tech.root: winstation
ms.assetid: 418d4d6a-9e4d-4fe3-8e1b-398c732c6e23
ms.date: 12/05/2018
ms.keywords: EnumWindowStations, EnumWindowStations function [Windows Stations and Desktops], EnumWindowStationsA, EnumWindowStationsW, _win32_enumwindowstations, base.enumwindowstations, winstation.enumwindowstations, winuser/EnumWindowStations, winuser/EnumWindowStationsA, winuser/EnumWindowStationsW
ms.topic: function
f1_keywords:
- winuser/EnumWindowStations
dev_langs:
- c++
req.header: winuser.h
req.include-header: Windows.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: EnumWindowStationsW (Unicode) and EnumWindowStationsA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: User32.lib
req.dll: User32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- User32.dll
api_name:
- EnumWindowStations
- EnumWindowStationsA
- EnumWindowStationsW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# EnumWindowStationsA function


## -description


Enumerates all window stations in the current session. The function passes the name of each window station, in turn, to an application-defined callback function.


## -parameters




### -param lpEnumFunc [in]

A pointer to an application-defined 
<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms682643(v=vs.85)">EnumWindowStationProc</a> callback function.


### -param lParam [in]

An application-defined value to be passed to the callback function.


## -returns



If the function succeeds, it returns the  nonzero value returned by the callback function that was pointed to by <i>lpEnumFunc</i>.

If the function is unable to perform the enumeration, the return value is zero. Call 
<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a> to get extended error information.

If the callback function fails, the return value is zero. The callback function can  call <a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-setlasterror">SetLastError</a> to set an error code for the caller to retrieve by calling <a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>.




## -remarks



The 
<b>EnumWindowStations</b> function enumerates only those window stations for which the calling process has the WINSTA_ENUMERATE access right. For more information, see 
<a href="https://docs.microsoft.com/windows/desktop/winstation/window-station-security-and-access-rights">Window Station Security and Access Rights</a>.

<b>EnumWindowStations</b> repeatedly invokes the <i>lpEnumFunc</i> callback function until the last window station is enumerated or the callback function returns FALSE.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms682643(v=vs.85)">EnumWindowStationProc</a>



<a href="https://docs.microsoft.com/windows/desktop/winstation/window-station-and-desktop-functions">Window Station and Desktop Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/winstation/window-stations">Window Stations</a>
 

 

