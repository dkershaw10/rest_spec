# List PimAlertSettings

Retrieve a list of pimalertsettings objects.
### Prerequisites
The following **scopes** are required to execute this API: ### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /AlertSettings
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$count|none|The count of related entities can be requested by specifying the $count query option.|
|$expand|string|Comma-separated list of relationships to expand and include in the response. See relationships table of [PimAlertSettings](../resources/pimalertsettings.md) for supported names. |
|$filter|string|Filter string that lets you filter the response based on a set of criteria.|
|$orderby|string|Comma-separated list of properties that are used to sort the order of items in the response collection.|
|$select|string|Comma-separated list of properties to include in the response.|
|$skip|int|The number of items to skip in a result set.|
|$skipToken|string|Paging token that is used to get the next set of results.|
|$top|int|The number of items to return in a result set.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [PimAlertSettings](../resources/pimalertsettings.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "alertsettings"
} -->
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 112
{
  "values": [
    {
      "AlertId": "AlertId-value",
      "AlertSettings": "AlertSettings-value"
    }
  ]
}
```
If successful, this method returns a `200 OK` response code and collection of [PimAlertSettings](../resources/pimalertsettings.md) objects in the response body.

<!-- uuid: de5dcc0d-0b14-4137-8b35-f16fb1f268ee
2015-10-15 04:04:54 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "List PimAlertSettings",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->