---
title: "Create settings"
description: "Create a new entitlementManagementSettings object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create settings
Namespace: microsoft.graph

Create a new entitlementManagementSettings object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST ** Collection URI for Microsoft.IGAELM.EC.FrontEnd.ExternalModel.entitlementManagementSettings not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [entitlementManagementSettings](../resources/entitlementmanagementsettings.md) object.

The following table shows the properties that are required when you create the [entitlementManagementSettings](../resources/entitlementmanagementsettings.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|externalUserLifecycleAction|String|**TODO: Add Description**|
|daysUntilExternalUserDeletedAfterBlocked|Int32|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and an [entitlementManagementSettings](../resources/entitlementmanagementsettings.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_entitlementmanagementsettings_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta** Collection URI for Microsoft.IGAELM.EC.FrontEnd.ExternalModel.entitlementManagementSettings not found
Content-Type: application/json
Content-length: 200

{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.entitlementManagementSettings",
  "externalUserLifecycleAction": "String",
  "daysUntilExternalUserDeletedAfterBlocked": "Integer"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IGAELM.EC.FrontEnd.ExternalModel.entitlementManagementSettings"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#Microsoft.IGAELM.EC.FrontEnd.ExternalModel.entitlementManagementSettings",
  "id": "e07f6d98-6d98-e07f-986d-7fe0986d7fe0",
  "externalUserLifecycleAction": "String",
  "daysUntilExternalUserDeletedAfterBlocked": "Integer"
}
```
