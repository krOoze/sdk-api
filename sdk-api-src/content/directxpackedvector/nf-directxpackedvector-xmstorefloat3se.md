---
UID: NF:directxpackedvector.XMStoreFloat3SE
title: XMStoreFloat3SE function (directxpackedvector.h)
description: Stores an XMVECTOR in an XMFLOAT3SE.
old-location: dxmath\xmstorefloat3se.htm
tech.root: dxmath
ms.assetid: M:Microsoft.directx_sdk.storing.XMStoreFloat3SE(XMFLOAT3SE@,XMVECTOR)
ms.date: 12/05/2018
ms.keywords: DirectX::PackedVector.XMStoreFloat3SE, XMStoreFloat3SE, XMStoreFloat3SE method [DirectX Math Support APIs], dxmath.xmstorefloat3se
ms.topic: function
f1_keywords:
- directxpackedvector/XMStoreFloat3SE
dev_langs:
- c++
req.header: directxpackedvector.h
req.include-header: DirectXPackedVector.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: DirectX::PackedVector
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
- directxpackedvector.inl
api_name:
- XMStoreFloat3SE
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# XMStoreFloat3SE function


## -description


Stores an <a href="https://docs.microsoft.com/windows/desktop/dxmath/xmvector-data-type">XMVECTOR</a> in an <a href="https://docs.microsoft.com/windows/desktop/api/directxpackedvector/ns-directxpackedvector-xmfloat3se">XMFLOAT3SE</a>.


## -parameters




### -param pDestination [out]

Address at which to store the data.


### -param V [in]

Vector containing the data to store.


## -returns



None.




## -remarks



The following pseudocode demonstrates the operation of the function.


```

  XMVECTOR N;

  static const XMVECTOR  Max = { 65472.f, 65427.f, 65427.f, 0 };
  N = XMVectorClamp(V, XMVectorZero(), Max);

  uint32_t m[3], e[3];
  ConvertToFloat14( N.x, &m[0], &e[0]);
  ConvertToFloat14( N.y, &m[1], &e[1]);
  ConvertToFloat14( N.z, &m[2], &e[2]);

  uint32_t T = XMMax( e[0], XMMax( e[1], e[2] ) );

  pDestination->xm = m[0] >> (T - e[0]);
  PDestination->ym = m[1] >> (T - e[1]);
  pDestination->zm = m[2] >> (T - e[2]);
  pDestination->e = T;

```


If the three components are not close to each other in magnitude, the largest value(s) will set the exponent and the
   other components will be shifted to zero.

<h3><a id="Platform_Requirements"></a><a id="platform_requirements"></a><a id="PLATFORM_REQUIREMENTS"></a>Platform Requirements</h3>
Microsoft Visual Studio 2010 or Microsoft Visual Studio 2012 with the Windows SDK for Windows 8. Supported for Win32 desktop apps, Windows Store apps, and Windows Phone 8 apps.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/dxmath/ovw-xnamath-reference-functions-storage">DirectXMath Library Vector Store Functions</a>
 

 

