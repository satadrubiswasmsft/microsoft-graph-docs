---
title: "accessPackage resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# accessPackage resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List accessPackages](../api/entitlementmanagement-list-accesspackages.md)|[accessPackage](../resources/accesspackage.md) collection|Get the accessPackage resources from the accessPackages navigation property.|
|[Create accessPackages](../api/entitlementmanagement-post-accesspackages.md)|[accessPackage](../resources/accesspackage.md)|Create a new accessPackage object.|
|[Update accessPackages](../api/entitlementmanagement-update-accesspackages.md)|[accessPackage](../resources/accesspackage.md)|Update the properties of an accessPackages object.|
|[Get accessPackages](../api/entitlementmanagement-get-accesspackage.md)|[accessPackage](../resources/accesspackage.md)|Read the properties and relationships of an [accessPackage](../resources/accesspackage.md) object.|
|[Delete accessPackages](../api/entitlementmanagement-delete-accesspackages.md)|None|Delete an [accessPackage](../resources/accesspackage.md) object.|
|[List accessPackages](../api/accesspackage-list.md)|[accessPackage](../resources/accesspackage.md) collection|Get a list of the [accessPackage](../resources/accesspackage.md) objects and their properties.|
|[Create accessPackage](../api/accesspackage-create.md)|[accessPackage](../resources/accesspackage.md)|Create a new [accessPackage](../resources/accesspackage.md) object.|
|[Get accessPackage](../api/accesspackage-get.md)|[accessPackage](../resources/accesspackage.md)|Read the properties and relationships of an [accessPackage](../resources/accesspackage.md) object.|
|[Update accessPackage](../api/accesspackage-update.md)|[accessPackage](../resources/accesspackage.md)|Update the properties of an [accessPackage](../resources/accesspackage.md) object.|
|[Delete accessPackage](../api/accesspackage-delete.md)|None|Deletes an [accessPackage](../resources/accesspackage.md) object.|
|[Search](../api/accesspackage-search.md)|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|[List accessPackageAssignmentPolicies](../api/accesspackage-list-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|Get the accessPackageAssignmentPolicy resources from the accessPackageAssignmentPolicies navigation property.|
|[Create accessPackageAssignmentPolicies](../api/accesspackage-post-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md)|Create a new accessPackageAssignmentPolicy object.|
|[Get accessPackageAssignmentPolicies](../api/accesspackage-get-accesspackageassignmentpolicy.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md)|Read the properties and relationships of an [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object.|
|[Update accessPackageAssignmentPolicies](../api/accesspackage-update-accesspackageassignmentpolicies.md)|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md)|Update the properties of an accessPackageAssignmentPolicies object.|
|[Delete accessPackageAssignmentPolicies](../api/accesspackage-delete-accesspackageassignmentpolicies.md)|None|Delete an [accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) object.|
|[List accessPackageCatalog](../api/accesspackage-list-accesspackagecatalog.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md) collection|Get the accessPackageCatalog resources from the accessPackageCatalog navigation property.|
|[Add accessPackageCatalog](../api/accesspackage-post-accesspackagecatalog.md)|[accessPackageCatalog](../resources/accesspackagecatalog.md)|Add accessPackageCatalog by posting to the accessPackageCatalog collection.|
|[Remove accessPackageCatalog](../api/accesspackage-delete-accesspackagecatalog.md)|None|Remove an [accessPackageCatalog](../resources/accesspackagecatalog.md) object.|
|[List accessPackageResourceRoleScopes](../api/accesspackage-list-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|Get the accessPackageResourceRoleScope resources from the accessPackageResourceRoleScopes navigation property.|
|[Create accessPackageResourceRoleScopes](../api/accesspackage-post-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Create a new accessPackageResourceRoleScope object.|
|[Get accessPackageResourceRoleScopes](../api/accesspackage-get-accesspackageresourcerolescope.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Read the properties and relationships of an [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|
|[Update accessPackageResourceRoleScopes](../api/accesspackage-update-accesspackageresourcerolescopes.md)|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md)|Update the properties of an accessPackageResourceRoleScopes object.|
|[Delete accessPackageResourceRoleScopes](../api/accesspackage-delete-accesspackageresourcerolescopes.md)|None|Delete an [accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|catalogId|String|**TODO: Add Description**|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description**|
|isHidden|Boolean|**TODO: Add Description**|
|isRoleScopesVisible|Boolean|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageAssignmentPolicies|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|**TODO: Add Description**|
|accessPackageCatalog|[accessPackageCatalog](../resources/accesspackagecatalog.md)|**TODO: Add Description**|
|accessPackageResourceRoleScopes|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.accessPackage",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackage",
  "id": "String (identifier)",
  "catalogId": "String",
  "displayName": "String",
  "description": "String",
  "isHidden": "Boolean",
  "isRoleScopesVisible": "Boolean",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)"
}
```
