---
UID: NF:iscsidsc.RemoveRadiusServerA
title: RemoveRadiusServerA function (iscsidsc.h)
description: RemoveRadiusServer function removes a Remote Authentication Dial-In User Service (RADIUS) server entry from the RADIUS server list with which an iSCSI initiator is configured.
old-location: iscsidisc\removeradiusserver.htm
tech.root: iSCSIDisc
ms.assetid: e096a91b-84de-4b7d-a0d6-1364746ec488
ms.date: 12/05/2018
ms.keywords: RemoveRadiusServer, RemoveRadiusServer function [iSCSI Discovery Library API], RemoveRadiusServerA, RemoveRadiusServerW, iscsidisc.removeradiusserver, iscsidsc/RemoveRadiusServer, iscsidsc/RemoveRadiusServerA, iscsidsc/RemoveRadiusServerW
ms.topic: function
f1_keywords:
- iscsidsc/RemoveRadiusServer
dev_langs:
- c++
req.header: iscsidsc.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: RemoveRadiusServerW (Unicode) and RemoveRadiusServerA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Iscsidsc.lib
req.dll: Iscsidsc.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Iscsidsc.dll
api_name:
- RemoveRadiusServer
- RemoveRadiusServerA
- RemoveRadiusServerW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RemoveRadiusServerA function


## -description


The <b>RemoveRadiusServer</b> function removes a Remote Authentication Dial-In User Service (RADIUS) server entry from the RADIUS server list with which an iSCSI initiator is configured.


## -parameters




### -param Address [in]

A string that represents the IP address or RADIUS server name.


## -returns



Returns <b>ERROR_SUCCESS</b> if the operation is successful. If the operation fails due to a socket connection error, this function will return a Winsock error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/iscsidsc/nf-iscsidsc-addradiusservera">AddRadiusServer</a>
 

 

