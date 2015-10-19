# Create PrivilegedSecurityAlert

Use this API to create a new PrivilegedSecurityAlert.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /PrivilegedSecurityAlerts

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object.


### Response
If successful, this method returns `201, Created` response code and [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_privilegedsecurityalert_from_privilegedsecurityalerts"
}-->
```http
POST /PrivilegedSecurityAlerts
```
In the request body, supply a JSON representation of [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.privilegedsecurityalert"
} -->
```http
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 596

{
  "AlertId": "AlertId-value",
  "NumberOfAffectedItems": 99,
  "AdditionalData": "AdditionalData-value",
  "AlertName": "AlertName-value",
  "AlertDescription": "AlertDescription-value",
  "LastModifiedTime": "datetime-value",
  "LastScannedTime": "datetime-value",
  "SeverityLevel": "SeverityLevel-value",
  "AlertType": "AlertType-value",
  "SecurityImpact": "SecurityImpact-value",
  "MitigationSteps": "MitigationSteps-value",
  "HowToPrevent": "HowToPrevent-value",
  "WasDismissed": true,
  "IsActive": true,
  "IsResolvable": true,
  "IsConfigurable": true,
  "Status": "Status-value"
}
```

<!-- uuid: 1169a4d0-cd39-4296-8ed0-a085dd28252f
2015-10-18 19:39:27 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create PrivilegedSecurityAlert",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->