---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-management device-configurations patch --device-configuration-id {deviceConfiguration-id} --body '{\
  "@odata.type": "#microsoft.graph.windows10GeneralConfiguration",\
  "description": "Description value",\
  "displayName": "Display Name value",\
  "version": 7,\
  "enterpriseCloudPrintDiscoveryEndPoint": "Enterprise Cloud Print Discovery End Point value",\
  "enterpriseCloudPrintOAuthAuthority": "Enterprise Cloud Print OAuth Authority value",\
  "enterpriseCloudPrintOAuthClientIdentifier": "Enterprise Cloud Print OAuth Client Identifier value",\
  "enterpriseCloudPrintResourceIdentifier": "Enterprise Cloud Print Resource Identifier value",\
  "enterpriseCloudPrintDiscoveryMaxLimit": 5,\
  "enterpriseCloudPrintMopriaDiscoveryResourceIdentifier": "Enterprise Cloud Print Mopria Discovery Resource Identifier value",\
  "searchBlockDiacritics": true,\
  "searchDisableAutoLanguageDetection": true,\
  "searchDisableIndexingEncryptedItems": true,\
  "searchEnableRemoteQueries": true,\
  "searchDisableIndexerBackoff": true,\
  "searchDisableIndexingRemovableDrive": true,\
  "searchEnableAutomaticIndexSizeManangement": true,\
  "diagnosticsDataSubmissionMode": "none",\
  "oneDriveDisableFileSync": true,\
  "smartScreenEnableAppInstallControl": true,\
  "personalizationDesktopImageUrl": "https://example.com/personalizationDesktopImageUrl/",\
  "personalizationLockScreenImageUrl": "https://example.com/personalizationLockScreenImageUrl/",\
  "bluetoothAllowedServices": [\
    "Bluetooth Allowed Services value"\
  ],\
  "bluetoothBlockAdvertising": true,\
  "bluetoothBlockDiscoverableMode": true,\
  "bluetoothBlockPrePairing": true,\
  "edgeBlockAutofill": true,\
  "edgeBlocked": true,\
  "edgeCookiePolicy": "allow",\
  "edgeBlockDeveloperTools": true,\
  "edgeBlockSendingDoNotTrackHeader": true,\
  "edgeBlockExtensions": true,\
  "edgeBlockInPrivateBrowsing": true,\
  "edgeBlockJavaScript": true,\
  "edgeBlockPasswordManager": true,\
  "edgeBlockAddressBarDropdown": true,\
  "edgeBlockCompatibilityList": true,\
  "edgeClearBrowsingDataOnExit": true,\
  "edgeAllowStartPagesModification": true,\
  "edgeDisableFirstRunPage": true,\
  "edgeBlockLiveTileDataCollection": true,\
  "edgeSyncFavoritesWithInternetExplorer": true,\
  "cellularBlockDataWhenRoaming": true,\
  "cellularBlockVpn": true,\
  "cellularBlockVpnWhenRoaming": true,\
  "defenderRequireRealTimeMonitoring": true,\
  "defenderRequireBehaviorMonitoring": true,\
  "defenderRequireNetworkInspectionSystem": true,\
  "defenderScanDownloads": true,\
  "defenderScanScriptsLoadedInInternetExplorer": true,\
  "defenderBlockEndUserAccess": true,\
  "defenderSignatureUpdateIntervalInHours": 6,\
  "defenderMonitorFileActivity": "disable",\
  "defenderDaysBeforeDeletingQuarantinedMalware": 12,\
  "defenderScanMaxCpu": 2,\
  "defenderScanArchiveFiles": true,\
  "defenderScanIncomingMail": true,\
  "defenderScanRemovableDrivesDuringFullScan": true,\
  "defenderScanMappedNetworkDrivesDuringFullScan": true,\
  "defenderScanNetworkFiles": true,\
  "defenderRequireCloudProtection": true,\
  "defenderCloudBlockLevel": "high",\
  "defenderPromptForSampleSubmission": "alwaysPrompt",\
  "defenderScheduledQuickScanTime": "11:58:49.3840000",\
  "defenderScanType": "disabled",\
  "defenderSystemScanSchedule": "everyday",\
  "defenderScheduledScanTime": "11:59:10.9990000",\
  "defenderDetectedMalwareActions": {\
    "@odata.type": "microsoft.graph.defenderDetectedMalwareActions",\
    "lowSeverity": "clean",\
    "moderateSeverity": "clean",\
    "highSeverity": "clean",\
    "severeSeverity": "clean"\
  },\
  "defenderFileExtensionsToExclude": [\
    "Defender File Extensions To Exclude value"\
  ],\
  "defenderFilesAndFoldersToExclude": [\
    "Defender Files And Folders To Exclude value"\
  ],\
  "defenderProcessesToExclude": [\
    "Defender Processes To Exclude value"\
  ],\
  "lockScreenAllowTimeoutConfiguration": true,\
  "lockScreenBlockActionCenterNotifications": true,\
  "lockScreenBlockCortana": true,\
  "lockScreenBlockToastNotifications": true,\
  "lockScreenTimeoutInSeconds": 10,\
  "passwordBlockSimple": true,\
  "passwordExpirationDays": 6,\
  "passwordMinimumLength": 5,\
  "passwordMinutesOfInactivityBeforeScreenTimeout": 14,\
  "passwordMinimumCharacterSetCount": 0,\
  "passwordPreviousPasswordBlockCount": 2,\
  "passwordRequired": true,\
  "passwordRequireWhenResumeFromIdleState": true,\
  "passwordRequiredType": "alphanumeric",\
  "passwordSignInFailureCountBeforeFactoryReset": 12,\
  "privacyAdvertisingId": "blocked",\
  "privacyAutoAcceptPairingAndConsentPrompts": true,\
  "privacyBlockInputPersonalization": true,\
  "startBlockUnpinningAppsFromTaskbar": true,\
  "startMenuAppListVisibility": "collapse",\
  "startMenuHideChangeAccountSettings": true,\
  "startMenuHideFrequentlyUsedApps": true,\
  "startMenuHideHibernate": true,\
  "startMenuHideLock": true,\
  "startMenuHidePowerButton": true,\
  "startMenuHideRecentJumpLists": true,\
  "startMenuHideRecentlyAddedApps": true,\
  "startMenuHideRestartOptions": true,\
  "startMenuHideShutDown": true,\
  "startMenuHideSignOut": true,\
  "startMenuHideSleep": true,\
  "startMenuHideSwitchAccount": true,\
  "startMenuHideUserTile": true,\
  "startMenuLayoutEdgeAssetsXml": "c3RhcnRNZW51TGF5b3V0RWRnZUFzc2V0c1htbA==",\
  "startMenuLayoutXml": "c3RhcnRNZW51TGF5b3V0WG1s",\
  "startMenuMode": "fullScreen",\
  "startMenuPinnedFolderDocuments": "hide",\
  "startMenuPinnedFolderDownloads": "hide",\
  "startMenuPinnedFolderFileExplorer": "hide",\
  "startMenuPinnedFolderHomeGroup": "hide",\
  "startMenuPinnedFolderMusic": "hide",\
  "startMenuPinnedFolderNetwork": "hide",\
  "startMenuPinnedFolderPersonalFolder": "hide",\
  "startMenuPinnedFolderPictures": "hide",\
  "startMenuPinnedFolderSettings": "hide",\
  "startMenuPinnedFolderVideos": "hide",\
  "settingsBlockSettingsApp": true,\
  "settingsBlockSystemPage": true,\
  "settingsBlockDevicesPage": true,\
  "settingsBlockNetworkInternetPage": true,\
  "settingsBlockPersonalizationPage": true,\
  "settingsBlockAccountsPage": true,\
  "settingsBlockTimeLanguagePage": true,\
  "settingsBlockEaseOfAccessPage": true,\
  "settingsBlockPrivacyPage": true,\
  "settingsBlockUpdateSecurityPage": true,\
  "settingsBlockAppsPage": true,\
  "settingsBlockGamingPage": true,\
  "windowsSpotlightBlockConsumerSpecificFeatures": true,\
  "windowsSpotlightBlocked": true,\
  "windowsSpotlightBlockOnActionCenter": true,\
  "windowsSpotlightBlockTailoredExperiences": true,\
  "windowsSpotlightBlockThirdPartyNotifications": true,\
  "windowsSpotlightBlockWelcomeExperience": true,\
  "windowsSpotlightBlockWindowsTips": true,\
  "windowsSpotlightConfigureOnLockScreen": "disabled",\
  "networkProxyApplySettingsDeviceWide": true,\
  "networkProxyDisableAutoDetect": true,\
  "networkProxyAutomaticConfigurationUrl": "https://example.com/networkProxyAutomaticConfigurationUrl/",\
  "networkProxyServer": {\
    "@odata.type": "microsoft.graph.windows10NetworkProxyServer",\
    "address": "Address value",\
    "exceptions": [\
      "Exceptions value"\
    ],\
    "useForLocalAddresses": true\
  },\
  "accountsBlockAddingNonMicrosoftAccountEmail": true,\
  "antiTheftModeBlocked": true,\
  "bluetoothBlocked": true,\
  "cameraBlocked": true,\
  "connectedDevicesServiceBlocked": true,\
  "certificatesBlockManualRootCertificateInstallation": true,\
  "copyPasteBlocked": true,\
  "cortanaBlocked": true,\
  "deviceManagementBlockFactoryResetOnMobile": true,\
  "deviceManagementBlockManualUnenroll": true,\
  "safeSearchFilter": "strict",\
  "edgeBlockPopups": true,\
  "edgeBlockSearchSuggestions": true,\
  "edgeBlockSendingIntranetTrafficToInternetExplorer": true,\
  "edgeSendIntranetTrafficToInternetExplorer": true,\
  "edgeRequireSmartScreen": true,\
  "edgeEnterpriseModeSiteListLocation": "Edge Enterprise Mode Site List Location value",\
  "edgeFirstRunUrl": "https://example.com/edgeFirstRunUrl/",\
  "edgeSearchEngine": {\
    "@odata.type": "microsoft.graph.edgeSearchEngineBase"\
  },\
  "edgeHomepageUrls": [\
    "Edge Homepage Urls value"\
  ],\
  "edgeBlockAccessToAboutFlags": true,\
  "smartScreenBlockPromptOverride": true,\
  "smartScreenBlockPromptOverrideForFiles": true,\
  "webRtcBlockLocalhostIpAddress": true,\
  "internetSharingBlocked": true,\
  "settingsBlockAddProvisioningPackage": true,\
  "settingsBlockRemoveProvisioningPackage": true,\
  "settingsBlockChangeSystemTime": true,\
  "settingsBlockEditDeviceName": true,\
  "settingsBlockChangeRegion": true,\
  "settingsBlockChangeLanguage": true,\
  "settingsBlockChangePowerSleep": true,\
  "locationServicesBlocked": true,\
  "microsoftAccountBlocked": true,\
  "microsoftAccountBlockSettingsSync": true,\
  "nfcBlocked": true,\
  "resetProtectionModeBlocked": true,\
  "screenCaptureBlocked": true,\
  "storageBlockRemovableStorage": true,\
  "storageRequireMobileDeviceEncryption": true,\
  "usbBlocked": true,\
  "voiceRecordingBlocked": true,\
  "wiFiBlockAutomaticConnectHotspots": true,\
  "wiFiBlocked": true,\
  "wiFiBlockManualConfiguration": true,\
  "wiFiScanInterval": 0,\
  "wirelessDisplayBlockProjectionToThisDevice": true,\
  "wirelessDisplayBlockUserInputFromReceiver": true,\
  "wirelessDisplayRequirePinForPairing": true,\
  "windowsStoreBlocked": true,\
  "appsAllowTrustedAppsSideloading": "blocked",\
  "windowsStoreBlockAutoUpdate": true,\
  "developerUnlockSetting": "blocked",\
  "sharedUserAppDataAllowed": true,\
  "appsBlockWindowsStoreOriginatedApps": true,\
  "windowsStoreEnablePrivateStoreOnly": true,\
  "storageRestrictAppDataToSystemVolume": true,\
  "storageRestrictAppInstallToSystemVolume": true,\
  "gameDvrBlocked": true,\
  "experienceBlockDeviceDiscovery": true,\
  "experienceBlockErrorDialogWhenNoSIM": true,\
  "experienceBlockTaskSwitcher": true,\
  "logonBlockFastUserSwitching": true,\
  "tenantLockdownRequireNetworkDuringOutOfBoxExperience": true\
}\
'

```