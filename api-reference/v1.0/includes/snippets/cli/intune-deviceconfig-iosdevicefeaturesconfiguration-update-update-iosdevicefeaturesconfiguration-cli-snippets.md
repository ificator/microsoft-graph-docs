---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-management device-configurations patch --device-configuration-id {deviceConfiguration-id} --body '{\
  "@odata.type": "#microsoft.graph.iosDeviceFeaturesConfiguration",\
  "description": "Description value",\
  "displayName": "Display Name value",\
  "version": 7,\
  "assetTagTemplate": "Asset Tag Template value",\
  "lockScreenFootnote": "Lock Screen Footnote value",\
  "homeScreenDockIcons": [\
    {\
      "@odata.type": "microsoft.graph.iosHomeScreenFolder",\
      "displayName": "Display Name value",\
      "pages": [\
        {\
          "@odata.type": "microsoft.graph.iosHomeScreenFolderPage",\
          "displayName": "Display Name value",\
          "apps": [\
            {\
              "@odata.type": "microsoft.graph.iosHomeScreenApp",\
              "displayName": "Display Name value",\
              "bundleID": "Bundle ID value"\
            }\
          ]\
        }\
      ]\
    }\
  ],\
  "homeScreenPages": [\
    {\
      "@odata.type": "microsoft.graph.iosHomeScreenPage",\
      "displayName": "Display Name value",\
      "icons": [\
        {\
          "@odata.type": "microsoft.graph.iosHomeScreenFolder",\
          "displayName": "Display Name value",\
          "pages": [\
            {\
              "@odata.type": "microsoft.graph.iosHomeScreenFolderPage",\
              "displayName": "Display Name value",\
              "apps": [\
                {\
                  "@odata.type": "microsoft.graph.iosHomeScreenApp",\
                  "displayName": "Display Name value",\
                  "bundleID": "Bundle ID value"\
                }\
              ]\
            }\
          ]\
        }\
      ]\
    }\
  ],\
  "notificationSettings": [\
    {\
      "@odata.type": "microsoft.graph.iosNotificationSettings",\
      "bundleID": "Bundle ID value",\
      "appName": "App Name value",\
      "publisher": "Publisher value",\
      "enabled": true,\
      "showInNotificationCenter": true,\
      "showOnLockScreen": true,\
      "alertType": "banner",\
      "badgesEnabled": true,\
      "soundsEnabled": true\
    }\
  ]\
}\
'

```