# Create OAuth2PermissionGrant

Use this API to create a new OAuth2PermissionGrant.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /groups

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [OAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.


### Response
If successful, this method returns `201, Created` response code and [OAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_oauth2permissiongrant_from_groups"
}-->
```http
POST /groups
```
In the request body, supply a JSON representation of [OAuth2PermissionGrant](../resources/oauth2permissiongrant.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.oauth2permissiongrant"
} -->
```http
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 271

{
  "clientId": "clientId-value",
  "consentType": "consentType-value",
  "expiryTime": "datetime-value",
  "objectId": "objectId-value",
  "principalId": "principalId-value",
  "resourceId": "resourceId-value",
  "scope": "scope-value",
  "startTime": "datetime-value"
}
```

<!-- uuid: 7b985f1a-e3d9-4a53-962f-8cb3eb5ec020
2015-10-25 14:25:33 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create OAuth2PermissionGrant",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->