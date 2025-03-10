---
UID: NE:vdshwprv._VDS_ISCSI_LOGIN_TYPE
title: VDS_ISCSI_LOGIN_TYPE (vdshwprv.h)
description: Defines the set of valid types for logging into an iSCSI target.
old-location: base\vds_iscsi_login_type.htm
tech.root: VDS
ms.assetid: d40db9ab-6fa5-4efb-83e8-ce1dce5fe0c2
ms.date: 12/05/2018
ms.keywords: VDS_ILT_BOOT, VDS_ILT_MANUAL, VDS_ILT_PERSISTENT, VDS_ISCSI_LOGIN_TYPE, VDS_ISCSI_LOGIN_TYPE enumeration [VDS], base.vds_iscsi_login_type, vds/VDS_ILT_BOOT, vds/VDS_ILT_MANUAL, vds/VDS_ILT_PERSISTENT, vds/VDS_ISCSI_LOGIN_TYPE, vdshwprv/VDS_ILT_BOOT, vdshwprv/VDS_ILT_MANUAL, vdshwprv/VDS_ILT_PERSISTENT, vdshwprv/VDS_ISCSI_LOGIN_TYPE
ms.topic: enum
f1_keywords:
- vdshwprv/VDS_ISCSI_LOGIN_TYPE
dev_langs:
- c++
req.header: vdshwprv.h
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
- VDS_ISCSI_LOGIN_TYPE
targetos: Windows
req.typenames: VDS_ISCSI_LOGIN_TYPE
req.redist: VDS 1.1
ms.custom: 19H1
---

# VDS_ISCSI_LOGIN_TYPE enumeration


## -description


<p class="CCE_Message">[Beginning with Windows 8 and Windows Server 2012, the <a href="https://docs.microsoft.com/windows/desktop/VDS/virtual-disk-service-portal">Virtual Disk Service</a> COM interface is superseded by the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/stormgmt/windows-storage-management-api-portal">Windows Storage Management API</a>.]

Defines the set of valid types for logging into an iSCSI target.


## -enum-fields




### -field VDS_ILT_MANUAL

A manual, one-time login is performed.


### -field VDS_ILT_PERSISTENT

A persistent login is performed.


### -field VDS_ILT_BOOT

A persistent login is performed such that the target is present at startup.


## -remarks



<div class="alert"><b>Note</b>  Additional constants might be added to the <b>VDS_ISCSI_LOGIN_TYPE</b> enumeration in future Windows versions. For this reason, your application must be designed to gracefully handle an unrecognized <b>VDS_ISCSI_LOGIN_TYPE</b> enumeration constant.</div>
<div> </div>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/vds/nf-vds-ivdsiscsiinitiatoradapter-logintotarget">IVdsIscsiInitiatorAdapter::LoginToTarget</a>



<a href="https://docs.microsoft.com/windows/desktop/VDS/vds-enumerations">VDS Enumerations</a>
 

 

