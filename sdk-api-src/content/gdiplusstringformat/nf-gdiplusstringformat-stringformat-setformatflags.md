---
UID: NF:gdiplusstringformat.StringFormat.SetFormatFlags
title: StringFormat::SetFormatFlags (gdiplusstringformat.h)
description: The StringFormat::SetFormatFlags method sets the format flags for this StringFormat object. The format flags determine most of the characteristics of a StringFormat object.
old-location: gdiplus\_gdiplus_CLASS_StringFormat_SetFormatFlags_flags_.htm
tech.root: gdiplus
ms.assetid: VS|gdicpp|~\gdiplus\gdiplusreference\classes\stringformatclass\stringformatmethods\setformatflags.htm
ms.date: 12/05/2018
ms.keywords: SetFormatFlags, SetFormatFlags method [GDI+], SetFormatFlags method [GDI+],StringFormat class, StringFormat class [GDI+],SetFormatFlags method, StringFormat.SetFormatFlags, StringFormat::SetFormatFlags, _gdiplus_CLASS_StringFormat_SetFormatFlags_flags_, gdiplus._gdiplus_CLASS_StringFormat_SetFormatFlags_flags_
ms.topic: method
f1_keywords:
- gdiplusstringformat/StringFormat.SetFormatFlags
dev_langs:
- c++
req.header: gdiplusstringformat.h
req.include-header: Gdiplus.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP, Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Gdiplus.lib
req.dll: Gdiplus.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Gdiplus.dll
api_name:
- StringFormat.SetFormatFlags
targetos: Windows
req.typenames: 
req.redist: 
req.product: GDI+ 1.0
ms.custom: 19H1
---

# StringFormat::SetFormatFlags


## -description


The <b>StringFormat::SetFormatFlags</b> method sets the format flags for this 
			<a href="https://docs.microsoft.com/windows/desktop/api/gdiplusstringformat/nl-gdiplusstringformat-stringformat">StringFormat</a> object. The format flags determine most of the characteristics of a 
			<b>StringFormat</b> object.


## -parameters




### -param flags [in]

Type: <b>INT</b>

Thirty-two bit value that specifies the format flags that control most of the characteristics of the 
					<a href="https://docs.microsoft.com/windows/desktop/api/gdiplusstringformat/nl-gdiplusstringformat-stringformat">StringFormat</a> object. The flags are set by applying a bitwise 
					<b>OR</b> to elements of the 
					<a href="https://docs.microsoft.com/windows/desktop/api/gdiplusenums/ne-gdiplusenums-stringformatflags">StringFormatFlags</a> enumeration. 


## -returns



Type: <strong>Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/gdiplustypes/ne-gdiplustypes-status">Status</a></b>
</strong>

If the method succeeds, it returns Ok, which is an element of the <a href="https://docs.microsoft.com/windows/desktop/api/gdiplustypes/ne-gdiplustypes-status">Status</a> enumeration.

If the method fails, it returns one of the other elements of the <a href="https://docs.microsoft.com/windows/desktop/api/gdiplustypes/ne-gdiplustypes-status">Status</a> enumeration.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/gdiplustypes/ne-gdiplustypes-status">Status</a>



<a href="https://docs.microsoft.com/windows/desktop/api/gdiplusstringformat/nl-gdiplusstringformat-stringformat">StringFormat</a>
 

 

