---
UID: NF:winstring.WindowsTrimStringStart
title: WindowsTrimStringStart function (winstring.h)
description: Removes all leading occurrences of a specified set of characters from the source string.
old-location: winrt\windowstrimstringstart.htm
tech.root: WinRT
ms.assetid: 88B9034D-D010-4C38-8F03-A5AF2FEC448B
ms.date: 12/05/2018
ms.keywords: WindowsTrimStringStart, WindowsTrimStringStart function [Windows Runtime], winrt.windowstrimstringstart, winstring/WindowsTrimStringStart
ms.topic: function
f1_keywords:
- winstring/WindowsTrimStringStart
dev_langs:
- c++
req.header: winstring.h
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
- DllExport
api_location:
- winstring.h
- API-MS-Win-Core-WinRT-String-l1-1-0.dll
- ComBase.dll
- API-MS-Win-Core-WinRT-String-L1-1-1.dll
api_name:
- WindowsTrimStringStart
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# WindowsTrimStringStart function


## -description


Removes all leading occurrences of a specified set of characters from the source string.


## -parameters




### -param string [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinRT/hstring">HSTRING</a></b>

The string to be trimmed.


### -param trimString [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinRT/hstring">HSTRING</a></b>

The characters to remove from <i>string</i>.


### -param newString [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinRT/hstring">HSTRING</a>*</b>

The string that remains after all occurrences of characters in the <i>trimString</i> parameter are removed from the start of <i>string</i>, or <b>NULL</b> if <i>trimString</i> contains all of the characters in <i>string</i>.


## -returns



Type: <b>HRESULT</b>

This function can return one of these values.

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
The  trimmed string was created successfully.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
<i>newString</i> is <b>NULL</b>, or <i>trimString</i> is empty.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Failed to allocate the trimmed string.

</td>
</tr>
</table>
 




## -remarks



Each call to the <b>WindowsTrimStringStart</b> function must be matched with a corresponding call to <a href="https://docs.microsoft.com/windows/desktop/api/winstring/nf-winstring-windowsdeletestring">WindowsDeleteString</a>





## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/winstring/nf-winstring-windowsdeletestring">WindowsDeleteString</a>
 

 

