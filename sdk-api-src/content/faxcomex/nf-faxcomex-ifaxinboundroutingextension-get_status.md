---
UID: NF:faxcomex.IFaxInboundRoutingExtension.get_Status
title: IFaxInboundRoutingExtension::get_Status (faxcomex.h)
description: The IFaxInboundRoutingExtension::get_Status property is a value that indicates whether the fax routing extension loaded and initialized successfully.
old-location: fax\_mfax_faxinboundroutingextension_cpp_mfax_faxinboundroutingextension_status_cpp.htm
tech.root: Fax
ms.assetid: VS|fax|~\fax\faxinta_n_96sz.htm
ms.date: 12/05/2018
ms.keywords: IFaxInboundRoutingExtension interface [Fax Service],Status property, IFaxInboundRoutingExtension.Status, IFaxInboundRoutingExtension.get_Status, IFaxInboundRoutingExtension::Status, IFaxInboundRoutingExtension::get_Status, Status property [Fax Service], Status property [Fax Service],IFaxInboundRoutingExtension interface, _mfax_faxinboundroutingextension.status, fax._mfax_faxinboundroutingextension_cpp_mfax_faxinboundroutingextension_status_cpp, fax._mfax_faxinboundroutingextension_status, faxcomex/IFaxInboundRoutingExtension::Status, faxcomex/IFaxInboundRoutingExtension::get_Status, get_Status
ms.topic: method
f1_keywords:
- faxcomex/IFaxInboundRoutingExtension.Status
dev_langs:
- c++
req.header: faxcomex.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
req.dll: Fxscomex.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Fxscomex.dll
api_name:
- IFaxInboundRoutingExtension.Status
- IFaxInboundRoutingExtension.get_Status
- IFaxInboundRoutingExtension.get_Status
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IFaxInboundRoutingExtension::get_Status


## -description


The <b>IFaxInboundRoutingExtension::get_Status</b> property is a value that indicates whether the fax routing extension loaded and initialized successfully. 

This property is read-only.


## -parameters


## -remarks



If the extension did not load successfully, the property indicates the reason for the failure, and <a href="https://docs.microsoft.com/previous-versions/windows/desktop/fax/-mfax-faxinboundroutingextension-initerrorcode-vb">IFaxInboundRoutingExtension::get_InitErrorCode</a> holds the last error code value. For more information, see <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/faxcomex/ne-faxcomex-fax_provider_status_enum">FAX_PROVIDER_STATUS_ENUM</a>.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/fax/-mfax-faxinboundroutingextension">FaxInboundRoutingExtension</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/faxcomex/nn-faxcomex-ifaxinboundroutingextension">IFaxInboundRoutingExtension</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/fax/-mfax-managing-routing-extensions-and-routing-methods">Visual Basic Example</a>
 

 

