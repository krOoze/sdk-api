---
UID: NE:cfapi.CF_CALLBACK_RENAME_FLAGS
title: CF_CALLBACK_RENAME_FLAGS (cfapi.h)
description: Call back flags to inform the sync provider that a placeholder under one of its sync roots is about to be renamed or moved.
old-location: cloudapi\cf_callback_rename_flags.htm
tech.root: cfApi
ms.assetid: 7506ED1D-F6A8-49EB-B03B-B629264DFBB2
ms.date: 12/05/2018
ms.keywords: CF_CALLBACK_RENAME_FLAGS, CF_CALLBACK_RENAME_FLAGS enumeration, CF_CALLBACK_RENAME_FLAG_IS_DIRECTORY, CF_CALLBACK_RENAME_FLAG_NONE, CF_CALLBACK_RENAME_FLAG_SOURCE_IN_SCOPE, CF_CALLBACK_RENAME_FLAG_TARGET_IN_SCOPE, cfapi/CF_CALLBACK_RENAME_FLAGS, cfapi/CF_CALLBACK_RENAME_FLAG_IS_DIRECTORY, cfapi/CF_CALLBACK_RENAME_FLAG_NONE, cfapi/CF_CALLBACK_RENAME_FLAG_SOURCE_IN_SCOPE, cfapi/CF_CALLBACK_RENAME_FLAG_TARGET_IN_SCOPE, cloudApi.cf_callback_rename_flags
ms.topic: enum
f1_keywords:
- cfapi/CF_CALLBACK_RENAME_FLAGS
dev_langs:
- c++
req.header: cfapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1709 [desktop apps only]
req.target-min-winversvr: Windows Server 2016 [desktop apps only]
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
- CfApi.h
api_name:
- CF_CALLBACK_RENAME_FLAGS
targetos: Windows
req.typenames: CF_CALLBACK_RENAME_FLAGS
req.redist: 
ms.custom: 19H1
---

# CF_CALLBACK_RENAME_FLAGS enumeration


## -description


Call back flags to inform the sync provider that a placeholder under one of its sync roots is about to be renamed or moved.


## -enum-fields




### -field CF_CALLBACK_RENAME_FLAG_NONE

No rename flag.


### -field CF_CALLBACK_RENAME_FLAG_IS_DIRECTORY

Flag set if the placeholder is a directory.


### -field CF_CALLBACK_RENAME_FLAG_SOURCE_IN_SCOPE

Flag set if the link to be renamed or moved is within a sync root managed by the sync process.


### -field CF_CALLBACK_RENAME_FLAG_TARGET_IN_SCOPE

Flag set if the rename or move target is in the same sync root of the source path.

