---
UID: NF:chstring.operator-less-than
title: operator<
description: 
ms.assetid: bc9b4545-b2a2-48b0-b650-d048860d1386
ms.date: 05/20/2019
ms.keywords: operator<
ms.topic: language-reference
f1_keywords:
- chstring/operator<
dev_langs:
- c++
targetos: Windows
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: chstring.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
- apiref
api_type:
- 
api_location:
- chstring.h
api_name:
- operator<
---

# operator<

## -description

<p class="CCE_Message">
[The <a href="https://docs.microsoft.com/windows/desktop/WmiSdk/chstring">CHString</a> class is part of the WMI Provider Framework which is now considered in final state, and no further development, enhancements, or updates will be available for non-security related issues affecting these libraries.
The <a href="https://docs.microsoft.com/previous-versions/windows/desktop/wmi_v2/windows-management-infrastructure">MI APIs</a> should be used for all new development.]

The **CHString** comparison operators compare two strings.
These operators are a convenient substitute for the case-sensitive <a href="https://docs.microsoft.com/windows/desktop/api/chstring/nf-chstring-chstring-compare">Compare</a> method.

## -parameters

### -param s1

Reference to the **CHString** to the left of the operator for this comparison.

### -param s2

Reference to the **CHString** to the right of the operator for this comparison.

## -returns

If the strings meet the comparison condition, the operators return a nonzero value.
Otherwise, 0 is returned.

## -remarks

#### Examples

The following code example shows the use of a **CHString** Comparison Operator:

```cpp
CHString s1( L"abc" );
CHString s2( L"abd" );

assert( s1 < s2 );
```

## -see-also

<a href="https://docs.microsoft.com/windows/desktop/WmiSdk/chstring">CHString</a>
