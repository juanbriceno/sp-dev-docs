---
title: ID element (AppPartConfigDefinition complexType)
manager: soliver
ms.date: 9/16/2015
ms.audience: Developer
ms.topic: reference
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: 9c9dd6a2-8f5c-28be-3a7a-77e2a6c9a87f
---

# ID element (AppPartConfigDefinition complexType) 

(AppPartConfigDefinition)

**Applies to**: SharePoint Add-ins | SharePoint Foundation 2013 | SharePoint Server 2013

The unique identifier of the app part.

> [!NOTE] 
> The string `app` appears as part of or all of some element, attribute, and file names because SharePoint Add-ins were originally called "apps for SharePoint." To ensure backward compatibility, the schemas have not been changed.

## Element information

|   |   |
|---|---|
| **Element type**  | GUID |
| **Namespace**  | `http://schemas.microsoft.com/sharepoint/2012/app/partconfiguration` |
| **Schema file**  | apppartconfig.xsd |

## Definition

```XML
    <xs:element name="Id" type="GUID" minOccurs="1" maxOccurs="1"></xs:element>
```

## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section.

### Parent elements

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Element</p></th>
<th align="left"><p>Type</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p><a href="apppartconfig-element-apppartconfigdefinition.md">AppPartConfig</a></p></td>
<td align="left"><p><a href="apppartconfigdefinition-complextype-apppartconfigdefinition.md">AppPartConfigDefinition</a></p></td>
<td align="left"><p>The top level node of an app part configuration file.</p></td>
</tr>
</tbody>
</table>

### Child elements

None.

### Attributes

None.

<br/>

<br/>







