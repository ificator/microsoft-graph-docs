---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-app-management mobile-apps patch --mobile-app-id {mobileApp-id} --body '{\
  "@odata.type": "#microsoft.graph.windowsWebApp",\
  "displayName": "Display Name value",\
  "description": "Description value",\
  "publisher": "Publisher value",\
  "largeIcon": {\
    "@odata.type": "microsoft.graph.mimeContent",\
    "type": "Type value",\
    "value": "dmFsdWU="\
  },\
  "isFeatured": true,\
  "privacyInformationUrl": "https://example.com/privacyInformationUrl/",\
  "informationUrl": "https://example.com/informationUrl/",\
  "owner": "Owner value",\
  "developer": "Developer value",\
  "notes": "Notes value",\
  "publishingState": "processing",\
  "appUrl": "https://example.com/appUrl/"\
}\
'

```