---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-management managed-devices patch --managed-device-id {managedDevice-id} --body '{\
  "@odata.type": "#microsoft.graph.managedDevice",\
  "userId": "User Id value",\
  "deviceName": "Device Name value",\
  "managedDeviceOwnerType": "company",\
  "deviceActionResults": [\
    {\
      "@odata.type": "microsoft.graph.deviceActionResult",\
      "actionName": "Action Name value",\
      "actionState": "pending",\
      "startDateTime": "2016-12-31T23:58:46.7156189-08:00",\
      "lastUpdatedDateTime": "2017-01-01T00:00:56.8321556-08:00"\
    }\
  ],\
  "enrolledDateTime": "2016-12-31T23:59:43.797191-08:00",\
  "lastSyncDateTime": "2017-01-01T00:02:49.3205976-08:00",\
  "operatingSystem": "Operating System value",\
  "complianceState": "compliant",\
  "jailBroken": "Jail Broken value",\
  "managementAgent": "mdm",\
  "osVersion": "Os Version value",\
  "easActivated": true,\
  "easDeviceId": "Eas Device Id value",\
  "easActivationDateTime": "2016-12-31T23:59:43.4878784-08:00",\
  "azureADRegistered": true,\
  "deviceEnrollmentType": "userEnrollment",\
  "activationLockBypassCode": "Activation Lock Bypass Code value",\
  "emailAddress": "Email Address value",\
  "azureADDeviceId": "Azure ADDevice Id value",\
  "deviceRegistrationState": "registered",\
  "deviceCategoryDisplayName": "Device Category Display Name value",\
  "isSupervised": true,\
  "exchangeLastSuccessfulSyncDateTime": "2017-01-01T00:00:45.8803083-08:00",\
  "exchangeAccessState": "unknown",\
  "exchangeAccessStateReason": "unknown",\
  "remoteAssistanceSessionUrl": "https://example.com/remoteAssistanceSessionUrl/",\
  "remoteAssistanceSessionErrorDetails": "Remote Assistance Session Error Details value",\
  "isEncrypted": true,\
  "userPrincipalName": "User Principal Name value",\
  "model": "Model value",\
  "manufacturer": "Manufacturer value",\
  "imei": "Imei value",\
  "complianceGracePeriodExpirationDateTime": "2016-12-31T23:56:44.951111-08:00",\
  "serialNumber": "Serial Number value",\
  "phoneNumber": "Phone Number value",\
  "androidSecurityPatchLevel": "Android Security Patch Level value",\
  "userDisplayName": "User Display Name value",\
  "configurationManagerClientEnabledFeatures": {\
    "@odata.type": "microsoft.graph.configurationManagerClientEnabledFeatures",\
    "inventory": true,\
    "modernApps": true,\
    "resourceAccess": true,\
    "deviceConfiguration": true,\
    "compliancePolicy": true,\
    "windowsUpdateForBusiness": true\
  },\
  "wiFiMacAddress": "Wi Fi Mac Address value",\
  "deviceHealthAttestationState": {\
    "@odata.type": "microsoft.graph.deviceHealthAttestationState",\
    "lastUpdateDateTime": "Last Update Date Time value",\
    "contentNamespaceUrl": "https://example.com/contentNamespaceUrl/",\
    "deviceHealthAttestationStatus": "Device Health Attestation Status value",\
    "contentVersion": "Content Version value",\
    "issuedDateTime": "2016-12-31T23:58:22.1231038-08:00",\
    "attestationIdentityKey": "Attestation Identity Key value",\
    "resetCount": 10,\
    "restartCount": 12,\
    "dataExcutionPolicy": "Data Excution Policy value",\
    "bitLockerStatus": "Bit Locker Status value",\
    "bootManagerVersion": "Boot Manager Version value",\
    "codeIntegrityCheckVersion": "Code Integrity Check Version value",\
    "secureBoot": "Secure Boot value",\
    "bootDebugging": "Boot Debugging value",\
    "operatingSystemKernelDebugging": "Operating System Kernel Debugging value",\
    "codeIntegrity": "Code Integrity value",\
    "testSigning": "Test Signing value",\
    "safeMode": "Safe Mode value",\
    "windowsPE": "Windows PE value",\
    "earlyLaunchAntiMalwareDriverProtection": "Early Launch Anti Malware Driver Protection value",\
    "virtualSecureMode": "Virtual Secure Mode value",\
    "pcrHashAlgorithm": "Pcr Hash Algorithm value",\
    "bootAppSecurityVersion": "Boot App Security Version value",\
    "bootManagerSecurityVersion": "Boot Manager Security Version value",\
    "tpmVersion": "Tpm Version value",\
    "pcr0": "Pcr0 value",\
    "secureBootConfigurationPolicyFingerPrint": "Secure Boot Configuration Policy Finger Print value",\
    "codeIntegrityPolicy": "Code Integrity Policy value",\
    "bootRevisionListInfo": "Boot Revision List Info value",\
    "operatingSystemRevListInfo": "Operating System Rev List Info value",\
    "healthStatusMismatchInfo": "Health Status Mismatch Info value",\
    "healthAttestationSupportedStatus": "Health Attestation Supported Status value"\
  },\
  "subscriberCarrier": "Subscriber Carrier value",\
  "meid": "Meid value",\
  "totalStorageSpaceInBytes": 8,\
  "freeStorageSpaceInBytes": 7,\
  "managedDeviceName": "Managed Device Name value",\
  "partnerReportedThreatState": "activated",\
  "requireUserEnrollmentApproval": true,\
  "managementCertificateExpirationDate": "2016-12-31T23:57:59.9789653-08:00",\
  "iccid": "Iccid value",\
  "udid": "Udid value",\
  "notes": "Notes value",\
  "ethernetMacAddress": "Ethernet Mac Address value",\
  "physicalMemoryInBytes": 5\
}\
'

```