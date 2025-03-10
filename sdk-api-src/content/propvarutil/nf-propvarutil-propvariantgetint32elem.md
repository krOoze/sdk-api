---
UID: NF:propvarutil.PropVariantGetInt32Elem
title: PropVariantGetInt32Elem function (propvarutil.h)
description: Extracts a single Int32 element from a PROPVARIANT of type VT_I4, VT_VECTOR | VT_I4, or VT_ARRAY | VT_I4.
old-location: properties\PropVariantGetInt32Elem.htm
tech.root: properties
ms.assetid: de7dc6d4-d85a-44cb-8af7-840fd6e68d5c
ms.date: 12/05/2018
ms.keywords: PropVariantGetInt32Elem, PropVariantGetInt32Elem function [Windows Properties], _shell_PropVariantGetInt32Elem, properties.PropVariantGetInt32Elem, propvarutil/PropVariantGetInt32Elem, shell.PropVariantGetInt32Elem
ms.topic: function
f1_keywords:
- propvarutil/PropVariantGetInt32Elem
dev_langs:
- c++
req.header: propvarutil.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 with SP1 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Propsys.lib
req.dll: Propsys.dll (version 6.0 or later)
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Propsys.dll
api_name:
- PropVariantGetInt32Elem
targetos: Windows
req.typenames: 
req.redist: Windows Desktop Search (WDS) 3.0
ms.custom: 19H1
---

# PropVariantGetInt32Elem function


## -description


Extracts a single Int32 element from a <a href="https://docs.microsoft.com/windows/desktop/api/propidl/ns-propidl-propvariant">PROPVARIANT</a> of type VT_I4, VT_VECTOR | VT_I4, or VT_ARRAY | VT_I4.


## -parameters




### -param propvar [in]

Type: <b>REFPROPVARIANT</b>

Reference to the source <a href="https://docs.microsoft.com/windows/desktop/api/propidl/ns-propidl-propvariant">PROPVARIANT</a> structure.


### -param iElem [in]

Type: <b>ULONG</b>

The vector or array index; otherwise, <i>iElem</i> must be 0.


### -param pnVal [out]

Type: <b>LONG*</b>

When this function, contains the extracted Int32 value.


## -returns



Type: <b>HRESULT</b>

If this function succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



This helper function works for <a href="https://docs.microsoft.com/windows/desktop/api/propidl/ns-propidl-propvariant">PROPVARIANT</a> structures of the following types: 
          
                

<ul>
<li>VT_I4</li>
<li>VT_VECTTOR | VT_I4</li>
<li>VT_ARRAY | VT_I4</li>
</ul>
If the source <a href="https://docs.microsoft.com/windows/desktop/api/propidl/ns-propidl-propvariant">PROPVARIANT</a> has type VT_I4, iElem must be 0. Otherwise, <i>iElem</i>  must be less than the number of elements in the vector or array. You can use <a href="https://docs.microsoft.com/windows/desktop/api/propvarutil/nf-propvarutil-propvariantgetelementcount">PropVariantGetElementCount</a>  to obtain the number of elements in the vector or array.


#### Examples

The following example uses this <a href="https://docs.microsoft.com/windows/desktop/api/propvarutil/nf-propvarutil-propvariantgetint32elem">PropVariantGetInt32Elem</a> with an interation statement to access the values in a <a href="https://docs.microsoft.com/windows/desktop/api/propidl/ns-propidl-propvariant">PROPVARIANT</a> structure.


```cpp
// PROPVARIANT propvar;
// assume propvar is initialized and valid

if ((propvar.vt & VT_TYPEMASK) == VT_I4)
{
    UINT cElem = PropVariantGetElementCount(propvar);
    HRESULT hr = <mark type="const">S_OK</mark>;

    for (UINT iElem = 0; SUCCEEDED(hr) && iElem < cElem; iElem ++)
    {
        LONG nValue;
        hr = PropVariantGetInt32Elem(propvar, iElem, &nValue);

        if (SUCCEEDED(hr))
        {
            // nValue is valid now
        }
    }
}
```





## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/propvarutil/nf-propvarutil-propvariantgetelem">PropVariantGetElem</a>
 

 

