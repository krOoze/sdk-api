---
UID: NN:d3d10effect.ID3D10EffectVariable
title: ID3D10EffectVariable (d3d10effect.h)
description: The ID3D10EffectVariable interface is the base class for all effect variables.
old-location: direct3d10\id3d10effectvariable.htm
tech.root: direct3d10
ms.assetid: VS|directx_sdk|~\id3d10effectvariable.htm
ms.date: 12/05/2018
ms.keywords: 8ca39e59-14b1-dd93-b1d0-8cf16752726e, ID3D10EffectVariable, ID3D10EffectVariable interface [Direct3D 10], ID3D10EffectVariable interface [Direct3D 10],described, d3d10effect/ID3D10EffectVariable, direct3d10.id3d10effectvariable
ms.topic: interface
f1_keywords:
- d3d10effect/ID3D10EffectVariable
dev_langs:
- c++
req.header: d3d10effect.h
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
req.lib: D3D10.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- D3D10.lib
- D3D10.dll
api_name:
- ID3D10EffectVariable
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ID3D10EffectVariable interface


## -description


The <b>ID3D10EffectVariable</b> interface is the base class for all effect variables.

The lifetime of an <b>ID3D10EffectVariable</b> object is equal to the lifetime of its parent <a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nn-d3d10effect-id3d10effect">ID3D10Effect</a> object.
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul><h3><a id="methods"></a>Methods</h3>The <b>ID3D10EffectVariable</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asblend">AsBlend</a>
</td>
<td align="left" width="63%">
Get a effect-blend variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asconstantbuffer">AsConstantBuffer</a>
</td>
<td align="left" width="63%">
Get a constant buffer.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asdepthstencil">AsDepthStencil</a>
</td>
<td align="left" width="63%">
Get a depth-stencil variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asdepthstencilview">AsDepthStencilView</a>
</td>
<td align="left" width="63%">
Get a depth-stencil-view variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asmatrix">AsMatrix</a>
</td>
<td align="left" width="63%">
Get a matrix variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asrasterizer">AsRasterizer</a>
</td>
<td align="left" width="63%">
Get a rasterizer variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asrendertargetview">AsRenderTargetView</a>
</td>
<td align="left" width="63%">
Get a render-target-view variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-assampler">AsSampler</a>
</td>
<td align="left" width="63%">
Get a sampler variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asscalar">AsScalar</a>
</td>
<td align="left" width="63%">
Get a scalar variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asshader">AsShader</a>
</td>
<td align="left" width="63%">
Get a shader variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asshaderresource">AsShaderResource</a>
</td>
<td align="left" width="63%">
Get a shader-resource variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asstring">AsString</a>
</td>
<td align="left" width="63%">
Get a string variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asvector">AsVector</a>
</td>
<td align="left" width="63%">
Get a vector variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getannotationbyindex">GetAnnotationByIndex</a>
</td>
<td align="left" width="63%">
Get an annotation by index.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getannotationbyname">GetAnnotationByName</a>
</td>
<td align="left" width="63%">
Get an annotation by name.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getdesc">GetDesc</a>
</td>
<td align="left" width="63%">
Get a description.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getelement">GetElement</a>
</td>
<td align="left" width="63%">
Get an array element.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbyindex">GetMemberByIndex</a>
</td>
<td align="left" width="63%">
Get a structure member by index.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbyname">GetMemberByName</a>
</td>
<td align="left" width="63%">
Get a structure member by name.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbysemantic">GetMemberBySemantic</a>
</td>
<td align="left" width="63%">
Get a structure member by semantic.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getparentconstantbuffer">GetParentConstantBuffer</a>
</td>
<td align="left" width="63%">
Get a constant buffer.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getrawvalue">GetRawValue</a>
</td>
<td align="left" width="63%">
Get data.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-gettype">GetType</a>
</td>
<td align="left" width="63%">
Get type information.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-isvalid">IsValid</a>
</td>
<td align="left" width="63%">
Compare the data type with the data stored.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-setrawvalue">SetRawValue</a>
</td>
<td align="left" width="63%">
Set data.

</td>
</tr>
</table> 


## -members

The <b>ID3D10EffectVariable</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asblend">AsBlend</a>
</td>
<td align="left" width="63%">
Get a effect-blend variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asconstantbuffer">AsConstantBuffer</a>
</td>
<td align="left" width="63%">
Get a constant buffer.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asdepthstencil">AsDepthStencil</a>
</td>
<td align="left" width="63%">
Get a depth-stencil variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asdepthstencilview">AsDepthStencilView</a>
</td>
<td align="left" width="63%">
Get a depth-stencil-view variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asmatrix">AsMatrix</a>
</td>
<td align="left" width="63%">
Get a matrix variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asrasterizer">AsRasterizer</a>
</td>
<td align="left" width="63%">
Get a rasterizer variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asrendertargetview">AsRenderTargetView</a>
</td>
<td align="left" width="63%">
Get a render-target-view variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-assampler">AsSampler</a>
</td>
<td align="left" width="63%">
Get a sampler variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asscalar">AsScalar</a>
</td>
<td align="left" width="63%">
Get a scalar variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asshader">AsShader</a>
</td>
<td align="left" width="63%">
Get a shader variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asshaderresource">AsShaderResource</a>
</td>
<td align="left" width="63%">
Get a shader-resource variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asstring">AsString</a>
</td>
<td align="left" width="63%">
Get a string variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-asvector">AsVector</a>
</td>
<td align="left" width="63%">
Get a vector variable.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getannotationbyindex">GetAnnotationByIndex</a>
</td>
<td align="left" width="63%">
Get an annotation by index.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getannotationbyname">GetAnnotationByName</a>
</td>
<td align="left" width="63%">
Get an annotation by name.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getdesc">GetDesc</a>
</td>
<td align="left" width="63%">
Get a description.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getelement">GetElement</a>
</td>
<td align="left" width="63%">
Get an array element.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbyindex">GetMemberByIndex</a>
</td>
<td align="left" width="63%">
Get a structure member by index.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbyname">GetMemberByName</a>
</td>
<td align="left" width="63%">
Get a structure member by name.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getmemberbysemantic">GetMemberBySemantic</a>
</td>
<td align="left" width="63%">
Get a structure member by semantic.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getparentconstantbuffer">GetParentConstantBuffer</a>
</td>
<td align="left" width="63%">
Get a constant buffer.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-getrawvalue">GetRawValue</a>
</td>
<td align="left" width="63%">
Get data.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-gettype">GetType</a>
</td>
<td align="left" width="63%">
Get type information.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-isvalid">IsValid</a>
</td>
<td align="left" width="63%">
Compare the data type with the data stored.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d3d10effect/nf-d3d10effect-id3d10effectvariable-setrawvalue">SetRawValue</a>
</td>
<td align="left" width="63%">
Set data.

</td>
</tr>
</table>Get a effect-blend variable.

Get a constant buffer.

Get a depth-stencil variable.

Get a depth-stencil-view variable.

Get a matrix variable.

Get a rasterizer variable.

Get a render-target-view variable.

Get a sampler variable.

Get a scalar variable.

Get a shader variable.

Get a shader-resource variable.

Get a string variable.

Get a vector variable.

Get an annotation by index.

Get an annotation by name.

Get a description.

Get an array element.

Get a structure member by index.

Get a structure member by name.

Get a structure member by semantic.

Get a constant buffer.

Get data.

Get type information.

Compare the data type with the data stored.

Set data.

 


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/direct3d10/d3d10-graphics-reference-effect-interfaces">Effect Interfaces (Direct3D 10)</a>
 

 

