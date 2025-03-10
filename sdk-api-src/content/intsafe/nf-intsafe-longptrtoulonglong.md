---
UID: NF:intsafe.LongPtrToULongLong
title: LongPtrToULongLong function (intsafe.h)
description: Converts a value of type LONG_PTR to a value of type ULONGLONG.
old-location: shell\LongPtrToULongLong.htm
tech.root: shell
ms.assetid: 1936b963-751c-46c6-a409-f1191c6940e7
ms.date: 12/05/2018
ms.keywords: LongPtrToULongLong, LongPtrToULongLong function [Windows Shell], _shell_LongPtrToULongLong, intsafe/LongPtrToULongLong, shell.LongPtrToULongLong
ms.topic: function
f1_keywords:
- intsafe/LongPtrToULongLong
dev_langs:
- c++
req.header: intsafe.h
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
- HeaderDef
api_location:
- Intsafe.h
api_name:
- LongPtrToULongLong
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# LongPtrToULongLong function


## -description


Converts a value of type <b>LONG_PTR</b> to a value of type <b>ULONGLONG</b>.


## -parameters




### -param lOperand [in]

Type: <b>LONG_PTR</b>

The value to be converted.


### -param pullResult [out]

Type: <b>ULONGLONG*</b>

A pointer to the converted value. In the case where the conversion causes a truncation of the original value, the function returns INTSAFE_E_ARITHMETIC_OVERFLOW and this parameter is not valid.


## -returns



Type: <b>HRESULT</b>

If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



This is one of a set of functions designed to provide type conversions and perform validity checks with minimal impact on performance.



