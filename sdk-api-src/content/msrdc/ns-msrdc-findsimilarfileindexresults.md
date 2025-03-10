---
UID: NS:msrdc.__MIDL___MIDL_itf_msrdc_0000_0000_0013
title: FindSimilarFileIndexResults (msrdc.h)
description: Contains the file index information that the ISimilarityTraitsTable::FindSimilarFileIndex method returned for a matching file.
old-location: rdc\findsimilarfileindexresults.htm
tech.root: rdc
ms.assetid: 2e0d39ab-d491-496e-8753-e7223a5c5029
ms.date: 12/05/2018
ms.keywords: FindSimilarFileIndexResults, FindSimilarFileIndexResults structure [Remote Differential Compression], fs.findsimilarfileindexresults, msrdc/FindSimilarFileIndexResults, rdc.findsimilarfileindexresults
ms.topic: struct
f1_keywords:
- msrdc/FindSimilarFileIndexResults
dev_langs:
- c++
req.header: msrdc.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista
req.target-min-winversvr: Windows Server 2008
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: MsRdc.idl
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
- MsRdc.h
api_name:
- FindSimilarFileIndexResults
targetos: Windows
req.typenames: FindSimilarFileIndexResults
req.redist: 
ms.custom: 19H1
---

# FindSimilarFileIndexResults structure


## -description


Contains the file index information that the <a href="https://docs.microsoft.com/windows/desktop/api/msrdc/nf-msrdc-isimilaritytraitstable-findsimilarfileindex">ISimilarityTraitsTable::FindSimilarFileIndex</a> method returned for a matching file.


## -struct-fields




### -field m_FileIndex

The index of the matching file in the similarity traits table.


### -field m_MatchCount

The number of traits that were matched. The valid range is from <b>MSRDC_MINIMUM_MATCHESREQUIRED</b> to 
      <b>MSRDC_MAXIMUM_MATCHESREQUIRED</b>.


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/msrdc/nf-msrdc-isimilaritytraitstable-findsimilarfileindex">ISimilarityTraitsTable::FindSimilarFileIndex</a>
 

 

