---
UID: NF:directxmath.XMVector2EqualIntR
title: XMVector2EqualIntR function (directxmath.h)
description: Tests whether two 2D vectors are equal, treating each component as an unsigned integer. In addition, this function returns a comparison value that can be examined using functions such as XMComparisonAllTrue.
old-location: dxmath\xmvector2equalintr.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.comparison.XMVector2EqualIntR(XMVECTOR,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: Use DirectX..XMVector2EqualIntR, XMVector2EqualIntR, XMVector2EqualIntR method [DirectX Math Support APIs], dxmath.xmvector2equalintr
ms.topic: function
f1_keywords:
- directxmath/XMVector2EqualIntR
dev_langs:
- c++
req.header: directxmath.h
req.include-header: DirectXMath.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: Use DirectX.
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- directxmathvector.inl
api_name:
- XMVector2EqualIntR
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMVector2EqualIntR function


## -description


Tests whether two 2D vectors are equal, treating each component as an unsigned integer. In addition, this function returns a comparison value that can be examined using functions such as <a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmcomparisonalltrue">XMComparisonAllTrue</a>.


## -parameters




### -param V1 [in]

2D vector.


### -param V2 [in]

2D vector.


## -returns



Returns a comparison value that can be examined using functions such as <a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmcomparisonalltrue">XMComparisonAllTrue</a>.




## -remarks



This function does the following test:


```
V1.x == V2.x
V1.y == V2.y
```


<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-vector2-comparison">DirectXMath Library 2D Vector Comparison Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/api/directxmath/nf-directxmath-xmvector2equalint">XMVector2EqualInt</a>
 

 

