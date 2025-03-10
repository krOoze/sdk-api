---
UID: NF:rpcproxy.CStdAsyncStubBuffer_Invoke
title: CStdAsyncStubBuffer_Invoke function (rpcproxy.h)
description: Implements the IRpcStubBuffer::Invoke method.
old-location: rpc\cstdasyncstubbuffer_invoke.htm
tech.root: Rpc
ms.assetid: 069A6E16-D96F-4E74-B511-77B6496FE966
ms.date: 12/05/2018
ms.keywords: CStdAsyncStubBuffer_Invoke, CStdAsyncStubBuffer_Invoke function [RPC], rpc.cstdasyncstubbuffer_invoke, rpcproxy/CStdAsyncStubBuffer_Invoke
ms.topic: function
f1_keywords:
- rpcproxy/CStdAsyncStubBuffer_Invoke
dev_langs:
- c++
req.header: rpcproxy.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2016 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Ole32.lib
req.dll: Ole32.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- ole32.dll
- API-MS-Win-Core-Com-MidlProxyStub-L1-1-0.dll
- COMBase.dll
api_name:
- CStdAsyncStubBuffer_Invoke
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# CStdAsyncStubBuffer_Invoke function


## -description


<p class="CCE_Message">[CStdAsyncStubBuffer_Invoke is not supported and may be altered or unavailable in the future.]

Implements the  <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nf-objidl-irpcstubbuffer-invoke">IRpcStubBuffer::Invoke</a> method. 


## -parameters




### -param pthis [in]

Pointer to  the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-irpcstubbuffer">IRpcStubBuffer</a> object. 


### -param _prpcmsg [in]

Pointer to the <a href="https://docs.microsoft.com/windows/desktop/api/objidl/ns-objidl-rpcolemessage">RPCOLEMESSAGE</a> structure. On input, the structure contains the marshalled input parameters. On output, the structure contains the marshalled output and return values.


### -param _pRpcChannelBuffer [in]

Interface pointer to an <a href="https://docs.microsoft.com/windows/desktop/api/objidl/nn-objidl-irpcchannelbuffer">IRpcChannelBuffer</a> object. Channel used for communication between the client and server.


## -returns



Returns S_OK on success. 




## -remarks



This function is used internally by proxies that are generated by MIDL.



