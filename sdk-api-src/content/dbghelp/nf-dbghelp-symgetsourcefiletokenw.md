---
UID: NF:dbghelp.SymGetSourceFileTokenW
title: SymGetSourceFileTokenW function (dbghelp.h)
description: Retrieves token for the specified source file from the source server.
old-location: base\symgetsourcefiletoken.htm
tech.root: Debug
ms.assetid: 7a8c7d68-421e-41fd-8cab-750c44a5f028
ms.date: 12/05/2018
ms.keywords: SymGetSourceFileToken, SymGetSourceFileToken function, SymGetSourceFileTokenW, base.symgetsourcefiletoken, dbghelp/SymGetSourceFileToken, dbghelp/SymGetSourceFileTokenW
ms.topic: function
f1_keywords:
- dbghelp/SymGetSourceFileToken
dev_langs:
- c++
req.header: dbghelp.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: SymGetSourceFileTokenW (Unicode) and SymGetSourceFileToken (ANSI)
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Dbghelp.lib
req.dll: Dbghelp.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Dbghelp.dll
api_name:
- SymGetSourceFileToken
- SymGetSourceFileToken
- SymGetSourceFileTokenW
targetos: Windows
req.typenames: 
req.redist: DbgHelp.dll 6.2 or later
ms.custom: 19H1
---

# SymGetSourceFileTokenW function


## -description


Retrieves token for the specified source file from the source server.


## -parameters




### -param hProcess [in]

A handle to a process. This handle must have been previously passed to the 
<a href="https://docs.microsoft.com/windows/desktop/api/dbghelp/nf-dbghelp-syminitialize">SymInitialize</a> function.


### -param Base [in]

The base address of the module. 


### -param FileSpec [in]

The name of the source file.


### -param Token [out]

A pointer to a 
buffer that receives the token.


### -param Size [out]

The size of the <i>Token</i> buffer, in bytes.


## -returns



If the function succeeds, the return value is <b>TRUE</b>.
						

If the function fails, the return value is <b>FALSE</b>. To retrieve extended error information, call 
<a href="https://docs.microsoft.com/windows/desktop/api/errhandlingapi/nf-errhandlingapi-getlasterror">GetLastError</a>.




## -remarks



All DbgHelp functions, such as this one, are single threaded. Therefore, calls from more than one thread to this function will likely result in unexpected behavior or memory corruption. To avoid this, you must synchronize all concurrent calls from more than one thread to this function.

To call the Unicode version of this function, define DBGHELP_TRANSLATE_TCHAR.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/Debug/dbghelp-functions">DbgHelp Functions</a>



<a href="https://docs.microsoft.com/windows/desktop/Debug/source-server-and-source-indexing">Source Server</a>
 

 

