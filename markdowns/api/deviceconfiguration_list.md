# List DeviceConfiguration

Retrieve a list of deviceconfiguration objects.
### Prerequisites
The following **scopes** are required to execute this API: ### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /deviceConfiguration
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$orderby|string|Comma-separated list of properties that are used to sort the order of items in the response collection.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [DeviceConfiguration](../resources/deviceconfiguration.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "deviceconfiguration"
} -->
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 415
{
  "values": [
    {
      "publicIssuerCertificates": [
        "publicIssuerCertificates-value"
      ],
      "cloudPublicIssuerCertificates": [
        "cloudPublicIssuerCertificates-value"
      ],
      "registrationQuota": 99,
      "maximumRegistrationInactivityPeriod": 99,
      "objectType": "objectType-value",
      "objectId": "objectId-value",
      "deletionTimestamp": "datetime-value"
    }
  ]
}
```
If successful, this method returns a `200 OK` response code and collection of [DeviceConfiguration](../resources/deviceconfiguration.md) objects in the response body.

<!-- uuid: e23c39aa-01e6-4008-a70f-d84712d6c6a7
2015-10-15 04:04:55 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "List DeviceConfiguration",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->