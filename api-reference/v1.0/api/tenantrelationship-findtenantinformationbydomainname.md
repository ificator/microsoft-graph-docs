---
title: "tenantRelationship: findTenantInformationByDomainName"
description: "Given a domain name, search for a tenant and read its tenant information."
author: "adimitui"
ms.localizationpriority: medium
ms.prod: "directory-management"
doc_type: apiPageType
---

# tenantRelationship: findTenantInformationByDomainName

Namespace: microsoft.graph

Given a domain name, search for a tenant and read its [tenantInformation](../resources/tenantInformation.md). You can use this API to validate tenant information and use the **tenantId** to [configure cross-tenant access settings between you and the tenant](../resources/crosstenantaccesspolicyconfigurationpartner.md).

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|CrossTenantInformation.ReadBasic.All|
|Delegated (personal Microsoft account)|None|
|Application|CrossTenantInformation.ReadBasic.All|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->

``` http
GET /tenantRelationships/findTenantInformationByDomainName(domainName='{id}')
```

## Function parameters

In the request URL, provide the following query parameters with values. The following table shows the parameters that must be used with this function.

| Parameter | Type | Description |
|:---|:---|:---|
| domainName | String | Primary domain name of an Azure AD tenant. |

## Request headers

|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [tenantInformation](../resources/tenantinformation.md) object in the response body.

## Examples

### Request

<!-- {
  "blockType": "request",
  "name": "tenantrelationshiprootthis.findtenantinformationbydomainname"
}
-->

``` http
GET https://graph.microsoft.com/v1.0/tenantRelationships/findTenantInformationByDomainName(domainName='contoso.com')
```

### Response

>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.tenantInformation"
}
-->

``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
    "@odata.context": "https://graph.microsoft.com/v1.0/$metadata#microsoft.graph.tenantInformation",
    "tenantId": "6babcaad-604b-40ac-a9d7-9fd97c0b779f",
    "federationBrandName": null,
    "displayName": "Contoso, Ltd",
    "defaultDomainName": "CONTOSO18839.onmicrosoft.com"
}
```
