---
UID: NS:d3d12.D3D12_FEATURE_DATA_FEATURE_LEVELS
title: D3D12_FEATURE_DATA_FEATURE_LEVELS (d3d12.h)
description: Describes info about the feature levels supported by the current graphics driver.
old-location: direct3d12\d3d12_feature_data_feature_levels.htm
tech.root: direct3d12
ms.assetid: 8C709889-0C7E-4D6D-84BD-1449BB8EA96A
ms.date: 12/05/2018
ms.keywords: D3D12_FEATURE_DATA_FEATURE_LEVELS, D3D12_FEATURE_DATA_FEATURE_LEVELS structure, d3d12/D3D12_FEATURE_DATA_FEATURE_LEVELS, direct3d12.d3d12_feature_data_feature_levels
ms.topic: struct
f1_keywords:
- d3d12/D3D12_FEATURE_DATA_FEATURE_LEVELS
dev_langs:
- c++
req.header: d3d12.h
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
- D3D12.h
api_name:
- D3D12_FEATURE_DATA_FEATURE_LEVELS
targetos: Windows
req.typenames: D3D12_FEATURE_DATA_FEATURE_LEVELS
req.redist: 
ms.custom: 19H1
---

# D3D12_FEATURE_DATA_FEATURE_LEVELS structure


## -description


Describes info about the <a href="https://docs.microsoft.com/windows/desktop/direct3d11/overviews-direct3d-11-devices-downlevel-intro">feature levels</a> supported by the current graphics driver.
        


## -struct-fields




### -field NumFeatureLevels

The number of <a href="https://docs.microsoft.com/windows/desktop/direct3d11/overviews-direct3d-11-devices-downlevel-intro">feature levels</a> in the array at <b>pFeatureLevelsRequested</b>.
          


### -field pFeatureLevelsRequested

A pointer to an array of <a href="https://docs.microsoft.com/windows/desktop/api/d3dcommon/ne-d3dcommon-d3d_feature_level">D3D_FEATURE_LEVEL</a>s that the application is requesting for the driver and hardware to evaluate.
          


### -field MaxSupportedFeatureLevel

The maximum <a href="https://docs.microsoft.com/windows/desktop/direct3d11/overviews-direct3d-11-devices-downlevel-intro">feature level</a> that the driver and hardware support.
          


## -remarks



See <a href="https://docs.microsoft.com/windows/desktop/api/d3d12/ne-d3d12-d3d12_feature">D3D12_FEATURE</a>.
      




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/direct3d12/direct3d-12-structures">Core Structures</a>



<a href="https://docs.microsoft.com/windows/desktop/api/d3d12/ne-d3d12-d3d12_feature">D3D12_FEATURE</a>
 

 

