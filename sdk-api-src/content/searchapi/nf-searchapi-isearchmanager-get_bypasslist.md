---
UID: NF:searchapi.ISearchManager.get_BypassList
title: ISearchManager::get_BypassList (searchapi.h)
description: Gets a proxy bypass list from the indexer. This list is used to determine which items or URLs are local and do not need to go through the proxy server. This list is set by calling ISearchManager::SetProxy.
old-location: search\_search_ISearchManager_get_BypassList.htm
tech.root: search
ms.assetid: VS|search|~\search\wds3x\reference\ifaces\indexmanagement\isearchmanager\get_bypasslist.htm
ms.date: 12/05/2018
ms.keywords: ISearchManager interface [search],get_BypassList method, ISearchManager.get_BypassList, ISearchManager::get_BypassList, _search_ISearchManager_get_BypassList, get_BypassList, get_BypassList method [search], get_BypassList method [search],ISearchManager interface, search._search_ISearchManager_get_BypassList, searchapi/ISearchManager::get_BypassList
ms.topic: method
f1_keywords:
- searchapi/ISearchManager.get_BypassList
dev_langs:
- c++
req.header: searchapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 with SP1 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Searchadmin.idl
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
- COM
api_location:
- Searchapi.h
api_name:
- ISearchManager.get_BypassList
targetos: Windows
req.typenames: 
req.redist: Windows Desktop Search (WDS) 3.0
ms.custom: 19H1
---

# ISearchManager::get_BypassList


## -description


Gets a proxy bypass list from the indexer. This list is used to determine which items or URLs are local and do not need to go through the proxy server. This list is set by calling <a href="https://docs.microsoft.com/windows/desktop/api/searchapi/nf-searchapi-isearchmanager-setproxy">ISearchManager::SetProxy</a>.
        


## -parameters




### -param ppszBypassList [out, retval]

Type: <b>LPWSTR*</b>

Receives a pointer to the proxy bypass list that is stored in the indexer.
                


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -remarks



The ReindexMatchingUrls code sample, available on <a href="http://go.microsoft.com/fwlink/p/?linkid=155654">Code Gallery</a> and the <a href="http://go.microsoft.com/fwlink/p/?linkid=129787">Windows 7 SDK</a>, demonstrates ways to specify which files to re-index and how.



