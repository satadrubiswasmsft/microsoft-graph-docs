---
title: "Get connectedOrganizations"
description: "Read the properties and relationships of a connectedOrganization object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get connectedOrganizations
Namespace: microsoft.graph

Read the properties and relationships of a [connectedOrganization](../resources/connectedorganization.md) object.

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
GET /identityGovernance/entitlementManagement/connectedOrganizations
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [connectedOrganization](../resources/connectedorganization.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_connectedorganization"
}
-->
``` http
GET https://graph.microsoft.com/beta/identityGovernance/entitlementManagement/connectedOrganizations
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IGAELM.PDS.FrontEnd.ExternalModel.connectedOrganization"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#Microsoft.IGAELM.PDS.FrontEnd.ExternalModel.connectedOrganization",
    "id": "dd492355-2355-dd49-5523-49dd552349dd",
    "displayName": "String",
    "description": "String",
    "createdBy": "String",
    "createdDateTime": "String (timestamp)",
    "modifiedBy": "String",
    "modifiedDateTime": "String (timestamp)",
    "identitySources": [
      {
        "@odata.type": "microsoft.graph.azureActiveDirectoryTenant"
      }
    ],
    "state": "String"
  }
}
```
