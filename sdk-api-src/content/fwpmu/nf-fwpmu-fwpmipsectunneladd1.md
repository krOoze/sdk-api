---
UID: NF:fwpmu.FwpmIPsecTunnelAdd1
title: FwpmIPsecTunnelAdd1 function (fwpmu.h)
description: Adds a new Internet Protocol Security (IPsec) tunnel mode policy to the system.
old-location: fwp\fwpmipsectunneladd1.htm
tech.root: fwp
ms.assetid: 9ae40cf5-7ecf-4399-b196-ae58fe55afdb
ms.date: 12/05/2018
ms.keywords: FWPM_TUNNEL_FLAG_ENABLE_VIRTUAL_IF_TUNNELING, FWPM_TUNNEL_FLAG_POINT_TO_POINT, FwpmIPsecTunnelAdd1, FwpmIpsecTunnelAdd1, FwpmIpsecTunnelAdd1 function [Filtering], fwp.fwpmipsectunneladd1, fwpmu/FwpmIpsecTunnelAdd1
ms.topic: function
f1_keywords:
- fwpmu/FwpmIpsecTunnelAdd1
dev_langs:
- c++
req.header: fwpmu.h
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
req.lib: Fwpuclnt.lib
req.dll: Fwpuclnt.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- DllExport
api_location:
- Fwpuclnt.dll
api_name:
- FwpmIpsecTunnelAdd1
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# FwpmIPsecTunnelAdd1 function


## -description


The <b>FwpmIPsecTunnelAdd1</b> function adds a new Internet Protocol Security (IPsec) tunnel mode policy to the system.
<div class="alert"><b>Note</b>  <b>FwpmIPsecTunnelAdd1</b> is the specific implementation of FwpmIPsecTunnelAdd used in Windows 7. See <a href="https://docs.microsoft.com/windows/desktop/FWP/wfp-version-independent-names-and-targeting-specific-versions-of-windows">WFP Version-Independent Names and Targeting Specific Versions of Windows</a> for more information. For Windows Vista, <a href="https://docs.microsoft.com/windows/desktop/api/fwpmu/nf-fwpmu-fwpmipsectunneladd0">FwpmIPsecTunnelAdd0</a> is available. For Windows 8, <a href="https://docs.microsoft.com/windows/desktop/api/fwpmu/nf-fwpmu-fwpmipsectunneladd2">FwpmIPsecTunnelAdd2</a> is available.</div><div> </div>

## -parameters




### -param engineHandle [in]

Type: <b>HANDLE</b>

A handle for an open session to the filter engine. Call <a href="https://docs.microsoft.com/windows/desktop/api/fwpmu/nf-fwpmu-fwpmengineopen0">FwpmEngineOpen0</a> to open a session to the filter engine.


### -param flags [in]

Type: <b>UINT32</b>

Possible values:

<table>
<tr>
<th>IPsec tunnel flag</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%"><a id="FWPM_TUNNEL_FLAG_POINT_TO_POINT"></a><a id="fwpm_tunnel_flag_point_to_point"></a><dl>
<dt><b>FWPM_TUNNEL_FLAG_POINT_TO_POINT</b></dt>
</dl>
</td>
<td width="60%">
Adds a point-to-point tunnel to the system.

</td>
</tr>
<tr>
<td width="40%"><a id="FWPM_TUNNEL_FLAG_ENABLE_VIRTUAL_IF_TUNNELING"></a><a id="fwpm_tunnel_flag_enable_virtual_if_tunneling"></a><dl>
<dt><b>FWPM_TUNNEL_FLAG_ENABLE_VIRTUAL_IF_TUNNELING</b></dt>
</dl>
</td>
<td width="60%">
Enables virtual interface-based IPsec tunnel mode.

</td>
</tr>
</table>
 


### -param mainModePolicy [in, optional]

Type: [FWPM_PROVIDER_CONTEXT1](https://docs.microsoft.com/windows/desktop/api/fwpmtypes/ns-fwpmtypes-fwpm_provider_context1)a>*</b>

The Main Mode policy for the IPsec tunnel.


### -param tunnelPolicy [in]

Type: [FWPM_PROVIDER_CONTEXT1](https://docs.microsoft.com/windows/desktop/api/fwpmtypes/ns-fwpmtypes-fwpm_provider_context1)a>*</b>

The Quick Mode policy for the IPsec tunnel.


### -param numFilterConditions [in]

Type: <b>UINT32</b>

Number of filter conditions present in the <i>filterConditions</i> parameter.


### -param filterConditions [in]

Type: <b>const FWPM_FILTER_CONDITION0*</b>

Array of filter conditions that describe the traffic which should be tunneled by IPsec.


### -param keyModKey [in, optional]

Type: <b>const GUID*</b>

Pointer to a GUID that uniquely identifies the keying module key.

If the caller supplies this parameter, only that keying module will be used for the tunnel. Otherwise, the default keying policy applies.


### -param sd [in, optional]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/winnt/ns-winnt-security_descriptor">PSECURITY_DESCRIPTOR</a></b>

The security information associated with the IPsec tunnel.


## -returns



Type: <b>DWORD</b>

<table>
<tr>
<th>Return code/value</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>ERROR_SUCCESS</b></dt>
<dt>0</dt>
</dl>
</td>
<td width="60%">
The IPsec tunnel mode policy was successfully added.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>FWP_E_INVALID_PARAMETER</b></dt>
<dt>0x80320035</dt>
</dl>
</td>
<td width="60%">
FWPM_TUNNEL_FLAG_POINT_TO_POINT was not set and conditions other than local/remote
   address were specified.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>FWP_E_* error code</b></dt>
<dt>0x80320001—0x80320039</dt>
</dl>
</td>
<td width="60%">
A Windows Filtering Platform (WFP) specific error. See <a href="https://docs.microsoft.com/windows/desktop/FWP/wfp-error-codes">WFP Error Codes</a> for details.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>RPC_* error code</b></dt>
<dt>0x80010001—0x80010122</dt>
</dl>
</td>
<td width="60%">
Failure to communicate with the remote or local firewall engine.

</td>
</tr>
</table>
 




## -remarks



This function cannot be called from within a read-only transaction. It will fail
with <b>FWP_E_INCOMPATIBLE_TXN</b>.  See <a href="https://docs.microsoft.com/windows/desktop/FWP/object-management">Object Management</a> for more information about transactions.




## -see-also




[FWPM_FILTER_CONDITION0](https://docs.microsoft.com/windows/desktop/api/fwpmtypes/ns-fwpmtypes-fwpm_filter_condition0)a>



[FWPM_PROVIDER_CONTEXT1](https://docs.microsoft.com/windows/desktop/api/fwpmtypes/ns-fwpmtypes-fwpm_provider_context1)a>
 

 

