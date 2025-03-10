---
UID: NF:d3d9.IDirect3DDevice9.SetVertexShaderConstantF
title: IDirect3DDevice9::SetVertexShaderConstantF (d3d9.h)
description: Sets a floating-point vertex shader constant.
old-location: direct3d9\idirect3ddevice9__setvertexshaderconstantf.htm
tech.root: direct3d9
ms.assetid: VS|directx_sdk|~\idirect3ddevice9__setvertexshaderconstantf.htm
ms.date: 12/05/2018
ms.keywords: IDirect3DDevice9 interface [Direct3D 9],SetVertexShaderConstantF method, IDirect3DDevice9.SetVertexShaderConstantF, IDirect3DDevice9::SetVertexShaderConstantF, SetVertexShaderConstantF, SetVertexShaderConstantF method [Direct3D 9], SetVertexShaderConstantF method [Direct3D 9],IDirect3DDevice9 interface, c6cef8bb-7ab4-497c-1aa2-2ca745f6bf1b, d3d9helper/IDirect3DDevice9::SetVertexShaderConstantF, direct3d9.idirect3ddevice9__setvertexshaderconstantf
ms.topic: method
f1_keywords:
- d3d9/IDirect3DDevice9.SetVertexShaderConstantF
dev_langs:
- c++
req.header: d3d9.h
req.include-header: D3D9.h
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
req.lib: D3D9.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- D3D9.lib
- D3D9.dll
api_name:
- IDirect3DDevice9.SetVertexShaderConstantF
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IDirect3DDevice9::SetVertexShaderConstantF


## -description


Sets a floating-point vertex shader constant.


## -parameters




### -param StartRegister [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

Register number that will contain the first constant value.


### -param pConstantData [in]

Type: <b>const float*</b>

Pointer to an array of constants.


### -param Vector4fCount [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

Number of four float vectors in the array of constants.


## -returns



Type: <b><a href="/windows/win32/com/structure-of-com-error-codes">HRESULT</a></b>

If the method succeeds, the return value is D3D_OK. If the method fails, the return value can be
     D3DERR_INVALIDCALL.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/d3d9helper/nn-d3d9helper-idirect3ddevice9">IDirect3DDevice9</a>
 

 

