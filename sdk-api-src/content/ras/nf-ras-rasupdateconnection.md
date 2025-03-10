---
UID: NF:ras.RasUpdateConnection
title: RasUpdateConnection function (ras.h)
description: The RasUpdateConnection function updates the tunnel endpoints of an Internet Key Exchange version 2 (IKEv2) connection.
old-location: rras\rasupdateconnection.htm
tech.root: RRAS
ms.assetid: ab4fd68c-acc0-4586-9d3d-b796e23d635d
ms.date: 12/05/2018
ms.keywords: RasUpdateConnection, RasUpdateConnection function [RAS], ras/RasUpdateConnection, rras.rasupdateconnection
ms.topic: function
f1_keywords:
- ras/RasUpdateConnection
dev_langs:
- c++
req.header: ras.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: Windows Server 2008 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Rasapi32.lib
req.dll: Rasapi32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Rasapi32.dll
api_name:
- RasUpdateConnection
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# RasUpdateConnection function


## -description


The 
<b>RasUpdateConnection</b> function updates the tunnel endpoints of an Internet Key Exchange version 2 (IKEv2) connection.


## -parameters




### -param hrasconn [in]

A handle to the IKEv2 RAS connection for which the tunnel endpoints are to be changed. This can be a handle returned by the 
<a href="https://docs.microsoft.com/windows/desktop/api/ras/nf-ras-rasdiala">RasDial</a> or 
<a href="https://docs.microsoft.com/windows/desktop/api/ras/nf-ras-rasenumconnectionsa">RasEnumConnections</a> function.


### -param lprasupdateconn [in]

A pointer to a <a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/dd408110(v=vs.85)">RASUPDATECONN</a> structure that contains the new tunnel endpoints  for the RAS connection specified by <i>hrasconn</i>.


## -returns



If the function succeeds, the return value is <b>ERROR_SUCCESS</b>.

If the function fails, the return value is one of the error codes from <a href="https://docs.microsoft.com/windows/desktop/RRAS/routing-and-remote-access-error-codes">Routing and Remote Access Error Codes</a> or Winerror.h.




## -remarks



Note that 32-bit applications that call <b>RasUpdateConnection</b> will fail when run on a 64-bit machine. The workaround is to write a 64-bit version of the application for 64-bit machines.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/RRAS/about-remote-access-service">Remote Access Service (RAS) Overview</a>



<a href="https://docs.microsoft.com/windows/desktop/RRAS/remote-access-service-functions">Remote Access Service Functions</a>
 

 

