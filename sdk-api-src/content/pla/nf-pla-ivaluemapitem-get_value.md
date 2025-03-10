---
UID: NF:pla.IValueMapItem.get_Value
title: IValueMapItem::get_Value (pla.h)
description: Retrieves or sets the value of the item.
old-location: pla\ivaluemapitem_value.htm
tech.root: PLA
ms.assetid: 3f7549aa-2ad6-40f4-ae09-c5130a9c3451
ms.date: 12/05/2018
ms.keywords: IValueMapItem interface [PLA],Value property, IValueMapItem.Value, IValueMapItem.get_Value, IValueMapItem::Value, IValueMapItem::get_Value, IValueMapItem::put_Value, Value property [PLA], Value property [PLA],IValueMapItem interface, base.ivaluemapitem_value, get_Value, pla.ivaluemapitem_value, pla/IValueMapItem::Value, pla/IValueMapItem::get_Value, pla/IValueMapItem::put_Value
ms.topic: method
f1_keywords:
- pla/IValueMapItem.Value
dev_langs:
- c++
req.header: pla.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
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
req.dll: Pla.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Pla.dll
api_name:
- IValueMapItem.Value
- IValueMapItem.get_Value
- IValueMapItem.put_Value
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IValueMapItem::get_Value


## -description


Retrieves or sets the value of the item.

This property is read/write.


## -parameters


## -remarks



The variant type is VT_UI8 if the <a href="https://docs.microsoft.com/windows/win32/api/pla/ne-pla-valuemaptype">ValueMapType</a> enumeration is plaIndex, plaFlag or plaFlagArray.

The variant type is VT_UI4 if <a href="https://docs.microsoft.com/windows/win32/api/pla/ne-pla-valuemaptype">ValueMapType</a> is plaValidation.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/pla/nf-pla-ivaluemap-get_value">IValueMap::Value</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/pla/nn-pla-ivaluemapitem">IValueMapItem</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/pla/nf-pla-ivaluemapitem-get_valuemaptype">IValueMapItem::ValueMapType</a>
 

 

