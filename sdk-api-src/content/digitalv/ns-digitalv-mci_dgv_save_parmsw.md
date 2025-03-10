---
UID: NS:digitalv.__unnamed_struct_23
title: MCI_DGV_SAVE_PARMSW (digitalv.h)
description: The MCI_DGV_SAVE_PARMS structure contains information for the MCI_SAVE command for digital-video devices.
old-location: multimedia\mci_dgv_save_parms.htm
tech.root: Multimedia
ms.assetid: a647099c-f5f8-4728-99a1-8b5b8c6b67bf
ms.date: 12/05/2018
ms.keywords: '*LPMCI_DGV_SAVE_PARMSW, MCI_DGV_SAVE_PARMS, MCI_DGV_SAVE_PARMS structure [Windows Multimedia], MCI_DGV_SAVE_PARMSW, _win32_MCI_DGV_SAVE_PARMS_str, digitalv/MCI_DGV_SAVE_PARMS, multimedia.mci_dgv_save_parms'
ms.topic: struct
f1_keywords:
- digitalv/MCI_DGV_SAVE_PARMS
dev_langs:
- c++
req.header: digitalv.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
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
- Digitalv.h
api_name:
- MCI_DGV_SAVE_PARMS
- MCI_DGV_SAVE_PARMSW
targetos: Windows
req.typenames: MCI_DGV_SAVE_PARMSW
req.redist: 
ms.custom: 19H1
---

# MCI_DGV_SAVE_PARMSW structure


## -description



The <b>MCI_DGV_SAVE_PARMS</b> structure contains information for the <a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-save">MCI_SAVE</a> command for digital-video devices.




## -struct-fields




### -field dwCallback

The low-order word specifies a window handle used for the MCI_NOTIFY flag.


### -field lpstrFileName

String for filename to save.


### -field rc

Rectangle containing positioning information. <a href="http://go.microsoft.com/fwlink/p/?linkid=16998">RECT</a> structures are handled differently in MCI than in other parts of Windows; in MCI, <b>rc.right</b> contains the width of the rectangle and <b>rc.bottom</b> contains its height.


## -remarks



When assigning data to the members of this structure, set the corresponding flags in the <i>fdwCommand</i> parameter of the <a href="https://docs.microsoft.com/previous-versions/dd757160(v=vs.85)">mciSendCommand</a> function to validate the members.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci">MCI</a>



<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-structures">MCI Structures</a>



<a href="https://docs.microsoft.com/windows/desktop/Multimedia/mci-save">MCI_SAVE</a>



<a href="http://go.microsoft.com/fwlink/p/?linkid=16998">RECT</a>



<a href="https://docs.microsoft.com/previous-versions/dd757160(v=vs.85)">mciSendCommand</a>
 

 

