---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-management device-compliance-policies patch --device-compliance-policy-id {deviceCompliancePolicy-id} --body '{\
  "@odata.type": "#microsoft.graph.iosCompliancePolicy",\
  "description": "Description value",\
  "displayName": "Display Name value",\
  "version": 7,\
  "passcodeBlockSimple": true,\
  "passcodeExpirationDays": 6,\
  "passcodeMinimumLength": 5,\
  "passcodeMinutesOfInactivityBeforeLock": 5,\
  "passcodePreviousPasscodeBlockCount": 2,\
  "passcodeMinimumCharacterSetCount": 0,\
  "passcodeRequiredType": "alphanumeric",\
  "passcodeRequired": true,\
  "osMinimumVersion": "Os Minimum Version value",\
  "osMaximumVersion": "Os Maximum Version value",\
  "securityBlockJailbrokenDevices": true,\
  "deviceThreatProtectionEnabled": true,\
  "deviceThreatProtectionRequiredSecurityLevel": "secured",\
  "managedEmailProfileRequired": true\
}\
'

```