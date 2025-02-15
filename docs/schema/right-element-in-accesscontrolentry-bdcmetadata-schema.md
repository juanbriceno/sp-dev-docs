---
title: Right Element in AccessControlEntry (BDCMetadata Schema)
description: Details on the Right Element in AccessControlEntry (BDCMetadata Schema)
manager: soliver
ms.date: 01/27/2021
ms.audience: Developer
ms.topic: reference
f1_keywords:
- VS.SharePointTools.BDC.Right
ms.prod: sharepoint
ms.localizationpriority: medium
ms.assetid: a2e4bd6c-2306-b657-7290-cc9c9b262911
---
# Right Element in AccessControlEntry (BDCMetadata Schema)

**Applies to**: SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013

Specifies a single access permission for an access control entry (ACE).

**Namespace**: `http://schemas.microsoft.com/windows/2007/BusinessDataCatalog`

**Schema**: BDCMetadata

```XML
<Right BdcRight = "String"> </Right>
```

## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

<table>
<colgroup>
<col width="20%" />
<col width="80%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Attribute</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>**BdcRight**</p></td>
<td align="left"><p>Required.</p>
<p>The permission available to the security principal holding the right.</p>
<p>The following table lists the possible values for this attribute.</p>
<div class="tableSection">
<table>
<colgroup>
<col width="20%" />
<col width="80%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Value</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>None</p></td>
<td align="left"><p>No permissions.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Execute</p></td>
<td align="left"><p>The represented security principal has the permission to invoke a **MethodInstance**.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>Edit</p></td>
<td align="left"><p>The represented security principal has permission to change the attributes of a metadata object or its relationship to other metadata objects.</p></td>
</tr>
<tr class="even">
<td align="left"><p>SetPermissions</p></td>
<td align="left"><p>The represented security principal has permission to change the set of permissions for a metadata object.</p></td>
</tr>
<tr class="odd">
<td align="left"><p>SelectableInClients</p></td>
<td align="left"><p>The represented security principal has permission to select the metadata object this right refers to. If a user does not have this permission, the metadata object should not be selectable.</p></td>
</tr>
</tbody>
</table>
</div></td>
</tr>
</tbody>
</table>

### Child elements

None.

### Parent elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left"><p>Element</p></th>
<th align="left"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p><span sdata="link"><a href="accesscontrolentry-element-in-accesscontrollist-bdcmetadata-schema.md">AccessControlEntry Element in AccessControlList (BDCMetadata Schema)</a></span></p></td>
<td align="left"><p>The **AccessControlEntry** element that contains this right.</p></td>
</tr>
</tbody>
</table>








