---
UID: NS:vds._VDS_PATH_ID
title: VDS_PATH_ID (vds.h)
description: Defines a unique identification for a path.
old-location: base\vds_path_id.htm
tech.root: VDS
ms.assetid: bfb786fc-eb03-4449-b631-fb85813c08c8
ms.date: 12/05/2018
ms.keywords: VDS_PATH_ID, VDS_PATH_ID structure [VDS], base.vds_path_id, vds/VDS_PATH_ID, vdshwprv/VDS_PATH_ID
ms.topic: struct
f1_keywords:
- vds/VDS_PATH_ID
dev_langs:
- c++
req.header: vds.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 R2 [desktop apps only]
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
- Vds.h
- VdsHwPrv.h
api_name:
- VDS_PATH_ID
targetos: Windows
req.typenames: VDS_PATH_ID
req.redist: VDS 1.1
ms.custom: 19H1
---

# VDS_PATH_ID structure


## -description


<p class="CCE_Message">[Beginning with Windows 8 and Windows Server 2012, the <a href="https://docs.microsoft.com/windows/desktop/VDS/virtual-disk-service-portal">Virtual Disk Service</a> COM interface is superseded by the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/stormgmt/windows-storage-management-api-portal">Windows Storage Management API</a>.]

Defines a unique 
   identification for a path.


## -struct-fields




### -field ullSourceId

The source ID for the path. If this is an 
      MPIO path, the source ID is the unique DSM ID.


### -field ullPathId

The ID of the path given by the MPIO DSM.


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/VDS/vds-structures">VDS Structures</a>



<a href="https://docs.microsoft.com/windows/desktop/api/vdshwprv/ns-vdshwprv-vds_path_info">VDS_PATH_INFO</a>
 

 

