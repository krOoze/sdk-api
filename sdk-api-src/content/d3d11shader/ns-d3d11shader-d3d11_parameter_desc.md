---
UID: NS:d3d11shader._D3D11_PARAMETER_DESC
title: D3D11_PARAMETER_DESC (d3d11shader.h)
description: Describes a function parameter.
old-location: direct3d11\d3d11_parameter_desc.htm
tech.root: direct3d11
ms.assetid: C6F1079C-A686-44EA-933B-9DE2D70CFA33
ms.date: 12/05/2018
ms.keywords: D3D11_PARAMETER_DESC, D3D11_PARAMETER_DESC structure [Direct3D 11], d3d11shader/D3D11_PARAMETER_DESC, direct3d11.d3d11_parameter_desc
ms.topic: struct
f1_keywords:
- d3d11shader/D3D11_PARAMETER_DESC
dev_langs:
- c++
req.header: d3d11shader.h
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
- D3D11Shader.h
api_name:
- D3D11_PARAMETER_DESC
targetos: Windows
req.typenames: D3D11_PARAMETER_DESC
req.redist: 
ms.custom: 19H1
---

# D3D11_PARAMETER_DESC structure


## -description


Describes a function parameter. 


## -struct-fields




### -field Name

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">LPCSTR</a></b>

The name of the function parameter.


### -field SemanticName

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">LPCSTR</a></b>

The HLSL <a href="https://docs.microsoft.com/windows/desktop/direct3dhlsl/dx-graphics-hlsl-semantics">semantic</a> that is associated with this function parameter. This name includes the index, for example, SV_Target[n].


### -field Type

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_shader_variable_type">D3D_SHADER_VARIABLE_TYPE</a></b>

A <a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_shader_variable_type">D3D_SHADER_VARIABLE_TYPE</a>-typed value that identifies the variable type for the parameter.


### -field Class

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_shader_variable_class">D3D_SHADER_VARIABLE_CLASS</a></b>

A <a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_shader_variable_class">D3D_SHADER_VARIABLE_CLASS</a>-typed value that identifies the variable class for the parameter as one of scalar, vector, matrix, object, and so on.


### -field Rows

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The number of rows for a matrix parameter.


### -field Columns

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The number of columns for a matrix parameter.


### -field InterpolationMode

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_interpolation_mode">D3D_INTERPOLATION_MODE</a></b>

A <a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_interpolation_mode">D3D_INTERPOLATION_MODE</a>-typed value that identifies the interpolation mode for the parameter.


### -field Flags

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_parameter_flags">D3D_PARAMETER_FLAGS</a></b>

A combination of <a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_parameter_flags">D3D_PARAMETER_FLAGS</a>-typed values that are combined by using a bitwise OR operation. The resulting value specifies semantic flags for the parameter.


### -field FirstInRegister

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The first input register for this parameter.


### -field FirstInComponent

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The first input register component for this parameter.


### -field FirstOutRegister

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The first output register for this parameter.


### -field FirstOutComponent

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">UINT</a></b>

The first output register component for this parameter.


## -remarks



Get a function-parameter description by calling <a href="https://docs.microsoft.com/windows/desktop/api/d3d11shader/nf-d3d11shader-id3d11functionparameterreflection-getdesc">ID3D11FunctionParameterReflection::GetDesc</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/d3d11shader/nf-d3d11shader-id3d11functionparameterreflection-getdesc">ID3D11FunctionParameterReflection::GetDesc</a>



<a href="https://docs.microsoft.com/windows/desktop/direct3d11/d3d11-graphics-reference-shader-structures">Shader Structures</a>
 

 

