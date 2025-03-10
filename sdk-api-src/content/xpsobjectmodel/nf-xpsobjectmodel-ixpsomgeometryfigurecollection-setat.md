---
UID: NF:xpsobjectmodel.IXpsOMGeometryFigureCollection.SetAt
title: IXpsOMGeometryFigureCollection::SetAt (xpsobjectmodel.h)
description: Replaces an IXpsOMGeometryFigure interface pointer at a specified location in the collection.
old-location: xps\ixpsomgeometryfigurecollection_setat.htm
tech.root: printdocs
ms.assetid: 59612109-8500-4bd9-a37c-120ef12aded4
ms.date: 12/05/2018
ms.keywords: IXpsOMGeometryFigureCollection interface [XPS Documents and Packaging],SetAt method, IXpsOMGeometryFigureCollection.SetAt, IXpsOMGeometryFigureCollection::SetAt, SetAt, SetAt method [XPS Documents and Packaging], SetAt method [XPS Documents and Packaging],IXpsOMGeometryFigureCollection interface, xps.ixpsomgeometryfigurecollection_setat, xpsobjectmodel/IXpsOMGeometryFigureCollection::SetAt
ms.topic: method
f1_keywords:
- xpsobjectmodel/IXpsOMGeometryFigureCollection.SetAt
dev_langs:
- c++
req.header: xpsobjectmodel.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 7, Windows Vista with SP2 and Platform Update for Windows Vista [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2008 R2, Windows Server 2008 with SP2 and Platform Update for Windows Server 2008 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: XpsObjectModel.idl
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
- xpsobjectmodel.h
api_name:
- IXpsOMGeometryFigureCollection.SetAt
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IXpsOMGeometryFigureCollection::SetAt


## -description


Replaces an <a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigure">IXpsOMGeometryFigure</a> interface pointer at a specified location in the collection.


## -parameters




### -param index [in]

The zero-based index in the collection where an <a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigure">IXpsOMGeometryFigure</a> interface pointer is to be replaced.


### -param geometryFigure [in]

The <a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigure">IXpsOMGeometryFigure</a> interface pointer that will replace current contents at the location specified by <i>index</i>.


## -returns



If the method succeeds, it returns S_OK; otherwise, it returns an <b>HRESULT</b> error code.




## -remarks



At the location specified by <i>index</i>, this method releases the <a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigure">IXpsOMGeometryFigure</a> interface referenced by the existing pointer, then writes the pointer that is passed in <i>geometryFigure</i>.

For more information about the collection methods, see  <a href="https://docs.microsoft.com/previous-versions/windows/desktop/dd372931(v=vs.85)">Working with XPS OM Collection Interfaces</a>.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigure">IXpsOMGeometryFigure</a>



<a href="https://docs.microsoft.com/windows/desktop/api/xpsobjectmodel/nn-xpsobjectmodel-ixpsomgeometryfigurecollection">IXpsOMGeometryFigureCollection</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/dd372931(v=vs.85)">Working with XPS OM Collection Interfaces</a>



<a href="http://go.microsoft.com/?linkid=8435939">XML Paper Specification</a>
 

 

