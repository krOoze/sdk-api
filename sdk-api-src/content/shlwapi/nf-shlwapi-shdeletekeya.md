---
UID: NF:shlwapi.SHDeleteKeyA
title: SHDeleteKeyA function (shlwapi.h)
description: Deletes a subkey and all its descendants. This function removes the key and all the key's values from the registry.
old-location: shell\SHDeleteKey.htm
tech.root: shell
ms.assetid: 3c46db08-52d8-48fa-bda5-3c087908a1d3
ms.date: 12/05/2018
ms.keywords: HKEY_CLASSES_ROOT, HKEY_CURRENT_CONFIG, HKEY_CURRENT_USER, HKEY_LOCAL_MACHINE, HKEY_PERFORMANCE_DATA, HKEY_USERS, SHDeleteKey, SHDeleteKey function [Windows Shell], SHDeleteKeyA, SHDeleteKeyW, _win32_SHDeleteKey, _win32_SHDeleteKey_cpp, shell.SHDeleteKey, shlwapi/SHDeleteKey, shlwapi/SHDeleteKeyA, shlwapi/SHDeleteKeyW
ms.topic: function
f1_keywords:
- shlwapi/SHDeleteKey
dev_langs:
- c++
req.header: shlwapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional, Windows XP [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: SHDeleteKeyW (Unicode) and SHDeleteKeyA (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Shlwapi.lib
req.dll: Shlwapi.dll (version 4.71 or later)
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Shlwapi.dll
- API-MS-Win-DownLevel-shlwapi-l2-1-0.dll
- ShCore.dll
- API-MS-Win-DownLevel-shlwapi-l2-1-1.dll
- API-MS-Win-ShCore-Registry-l1-1-0.dll
- API-MS-Win-ShCore-Registry-l1-1-1.dll
api_name:
- SHDeleteKey
- SHDeleteKeyA
- SHDeleteKeyW
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# SHDeleteKeyA function


## -description


Deletes a subkey and all its descendants. This function removes the key and all the key's values from the registry.


## -parameters




### -param hkey [in]

Type: <b>HKEY</b>

A handle to an open registry key, or one of the following <a href="https://docs.microsoft.com/windows/desktop/SysInfo/predefined-keys">predefined keys</a>:

<a id="HKEY_CLASSES_ROOT"></a>
<a id="hkey_classes_root"></a>


#### HKEY_CLASSES_ROOT

<a id="HKEY_CURRENT_CONFIG"></a>
<a id="hkey_current_config"></a>


#### HKEY_CURRENT_CONFIG

<a id="HKEY_CURRENT_USER"></a>
<a id="hkey_current_user"></a>


#### HKEY_CURRENT_USER

<a id="HKEY_LOCAL_MACHINE"></a>
<a id="hkey_local_machine"></a>


#### HKEY_LOCAL_MACHINE

<a id="HKEY_PERFORMANCE_DATA"></a>
<a id="hkey_performance_data"></a>


#### HKEY_PERFORMANCE_DATA

<a id="HKEY_USERS"></a>
<a id="hkey_users"></a>


#### HKEY_USERS


### -param pszSubKey [in, optional]

Type: <b>LPCTSTR</b>

The address of a null-terminated string specifying the name of the key to delete.


## -returns



Type: <b>LSTATUS</b>

Returns <b>ERROR_SUCCESS</b> if successful, or a nonzero error code defined in Winerror.h otherwise. You can use the <a href="https://docs.microsoft.com/windows/desktop/api/winbase/nf-winbase-formatmessage">FormatMessage</a> function with the <b>FORMAT_MESSAGE_FROM_SYSTEM</b> flag to retrieve a generic description of the error.




## -remarks



Alternatively, use the <a href="https://docs.microsoft.com/windows/desktop/api/winreg/nf-winreg-regdeletekeya">RegDeleteKey</a> or <a href="https://docs.microsoft.com/windows/desktop/api/winreg/nf-winreg-regdeletetreea">RegDeleteTree</a> function.



