---
title: Master.ConvertToGroupCanceled Event (Visio)
keywords: vis_sdr.chm10719370
f1_keywords:
- vis_sdr.chm10719370
ms.prod: visio
api_name:
- Visio.Master.ConvertToGroupCanceled
ms.assetid: b585e434-fd81-93ae-92a6-5cc1d21c1afa
ms.date: 06/08/2017
---


# Master.ConvertToGroupCanceled Event (Visio)

Occurs after an event handler has returned  **True** (cancel) to a **QueryCancelConvertToGroup** event.


## Syntax

Private Sub  _expression_ _**ConvertToGroupCanceled**( **_ByVal Selection As [IVSELECTION]_** )

 _expression_ A variable that represents a **Master** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Selection_|Required| **[IVSELECTION]**|The selection of shapes that was going to be grouped.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/de8f5c7a-421d-ebcf-22b6-4310a202ef64%28Office.15%29.aspx).


