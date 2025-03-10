---
UID: NE:wuapi.tagDeploymentAction
title: DeploymentAction (wuapi.h)
description: Defines the action for which an update is explicitly deployed.
old-location: wua\deploymentaction.htm
tech.root: Wua_Sdk
ms.assetid: c192db44-05ad-4fb2-aa51-9153389d95dc
ms.date: 12/05/2018
ms.keywords: DeploymentAction, DeploymentAction enumeration [Windows Update Agent], daDetection, daInstallation, daNone, daUninstallation, wua.deploymentaction, wuapi/DeploymentAction, wuapi/daDetection, wuapi/daInstallation, wuapi/daNone, wuapi/daUninstallation
ms.topic: enum
f1_keywords:
- wuapi/DeploymentAction
dev_langs:
- c++
req.header: wuapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP, Windows 2000 Professional with SP3 [desktop apps only]
req.target-min-winversvr: Windows Server 2003, Windows 2000 Server with SP3 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Wuapi.idl
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
- Wuapi.h
api_name:
- DeploymentAction
targetos: Windows
req.typenames: DeploymentAction
req.redist: 
ms.custom: 19H1
---

# DeploymentAction enumeration


## -description


Defines the action for which an update is explicitly deployed.


## -enum-fields




### -field daNone

No explicit deployment action is specified on the update. The update  inherits the value from its bundled updates.


### -field daInstallation

The update should be installed on the computer and/or for the specified user.


### -field daUninstallation

The update should be uninstalled from the computer and/or for the specified user.


### -field daDetection

The update is deployed only to determine the applicability of the update. The update will not be installed.

