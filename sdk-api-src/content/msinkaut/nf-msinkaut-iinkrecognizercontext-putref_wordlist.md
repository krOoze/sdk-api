---
UID: NF:msinkaut.IInkRecognizerContext.putref_WordList
title: IInkRecognizerContext::putref_WordList (msinkaut.h)
description: Gets or sets the word list that is used in the recognition process to improve the recognition results.
old-location: tablet\inkrecognizercontext_wordlist.htm
tech.root: tablet
ms.assetid: 893950d4-c19c-4635-ad66-6e363860280a
ms.date: 12/05/2018
ms.keywords: 893950d4-c19c-4635-ad66-6e363860280a, IInkRecognizerContext interface [Tablet PC],WordList property, IInkRecognizerContext.WordList, IInkRecognizerContext.putref_WordList, IInkRecognizerContext::WordList, IInkRecognizerContext::get_WordList, IInkRecognizerContext::putref_WordList, InkRecognizerContext.get_WordList, WordList property [Tablet PC], WordList property [Tablet PC],IInkRecognizerContext interface, get_WordList, msinkaut/IInkRecognizerContext::WordList, msinkaut/IInkRecognizerContext::get_WordList, msinkaut/IInkRecognizerContext::putref_WordList, putref_WordList, tablet.inkrecognizercontext_wordlist
ms.topic: method
f1_keywords:
- msinkaut/IInkRecognizerContext.WordList
dev_langs:
- c++
req.header: msinkaut.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP Tablet PC Edition [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: InkObj.dll
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- InkObj.dll
- InkObj.dll.dll
api_name:
- IInkRecognizerContext.WordList
- IInkRecognizerContext.get_WordList
- InkRecognizerContext.get_WordList
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IInkRecognizerContext::putref_WordList


## -description



Gets or sets the word list that is used in the recognition process to improve the recognition results.



This property is read/write.


## -parameters


## -remarks



Setting this property succeeds only if the <a href="https://docs.microsoft.com/windows/desktop/api/msinkaut15/nf-msinkaut15-iinkdivisionresult-get_strokes">Strokes</a> property is <b>NULL</b>. You must set the <b>WordList</b> property before you attach an <a href="https://docs.microsoft.com/previous-versions/windows/desktop/legacy/ms703293(v=vs.85)">InkStrokes</a> collection to the <b>Strokes</b> property of the <a href="https://docs.microsoft.com/windows/desktop/tablet/inkrecognizercontext-class">InkRecognizerContext</a> or you must set the <b>Strokes</b> property to <b>NULL</b> and then set the <b>WordList</b> property (and possibly reattach the InkStrokes collection).

To remove the current word list and use the user dictionary, set this property to <b>NULL</b>. Any subsequent modification of the <a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList</a> object does not modify the recognition outcome. If you want to change the word list, first set this property to <b>NULL</b>, modify the InkWordList, and then re-attach it to the InkRecognizerContext by assigning it to the <b>WordList</b> property.

Use the <a href="https://docs.microsoft.com/windows/desktop/api/msinkaut/nf-msinkaut-iinkrecognizercontext-get_factoid">Factoid</a> property to limit the search to the word list that is associated with the context. You may also need to set the <a href="https://docs.microsoft.com/windows/desktop/api/msinkaut/nf-msinkaut-iinkrecognizercontext-get_recognitionflags">RecognitionFlags</a> property to improve the results.

Wordlist cannot be set after a factoid is set. This prevents a factoid from referring to a possibly non existent wordlist. Attempting to do so will result in an E_FAIL HRESULT value.

If a string is added to a word list, its capitalized versions are also implicitly added. For instance, adding "hello" implicitly adds "Hello" and "HELLO".

Using words longer than 256 characters will result in an E_POINTER exception when assigning the <b>WordList</b> property to <a href="https://docs.microsoft.com/windows/desktop/tablet/inkrecognizercontext-class">InkRecognizerContext</a>.




## -see-also




<a href="https://msdn.microsoft.com/en-us/library/Mt846801(v=VS.85).aspx">IInkRecognizerContext</a>



<a href="https://docs.microsoft.com/windows/desktop/tablet/inkrecognizercontext-class">InkRecognizerContext Class</a>



<a href="https://docs.microsoft.com/windows/desktop/tablet/inkwordlist-class">InkWordList Class</a>
 

 

