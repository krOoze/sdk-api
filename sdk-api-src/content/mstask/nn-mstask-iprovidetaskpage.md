---
UID: NN:mstask.IProvideTaskPage
title: IProvideTaskPage (mstask.h)
description: Provides the methods to access the property sheet settings of a task.
old-location: taskschd\iprovidetaskpage.htm
tech.root: taskschd
ms.assetid: 58be7ea9-022f-46a0-9f27-9b226000a8cc
ms.date: 12/05/2018
ms.keywords: IProvideTaskPage, IProvideTaskPage interface [Task Scheduler], IProvideTaskPage interface [Task Scheduler],described, _msb_iprovidetaskpage, mstask/IProvideTaskPage, taskschd.iprovidetaskpage
ms.topic: interface
f1_keywords:
- mstask/IProvideTaskPage
dev_langs:
- c++
req.header: mstask.h
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
req.lib: Mstask.lib
req.dll: Mstask.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Mstask.dll
api_name:
- IProvideTaskPage
targetos: Windows
req.typenames: 
req.redist: Internet Explorer 4.0 or later on Windows NT 4.0 and Windows 95
ms.custom: 19H1
---

# IProvideTaskPage interface


## -description


<p class="CCE_Message">[[This API may be altered or unavailable in subsequent versions of the operating system or product. Please use the <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/task-scheduler-2-0-interfaces">Task Scheduler 2.0 Interfaces</a> instead.] ]

Provides the methods to access the property sheet settings of a task.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IProvideTaskPage</b> interface inherits from the <a href="https://docs.microsoft.com/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IProvideTaskPage</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IProvideTaskPage</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-iprovidetaskpage-getpage">GetPage</a>
</td>
<td align="left" width="63%">
Retrieves the property sheet pages associated with a task.

</td>
</tr>
</table> 


## -remarks



This is the primary interface of the <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/t">task object</a>. To create a task object, call 
<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-itaskscheduler-activate">ITaskScheduler::Activate</a> for existing tasks or 
<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-itaskscheduler-newworkitem">ITaskScheduler::NewWorkItem</a> for new tasks.


#### Examples

For more information and example code for this interface, see <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/c-c-code-example-retrieving-a-task-page">C/C++ Code Example: Retrieving a Task Page</a>.

<div class="code"></div>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-itaskscheduler-activate">ITaskScheduler::Activate</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-itaskscheduler-newworkitem">ITaskScheduler::NewWorkItem</a>
 

 

