---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



result, err := graphClient.DeviceAppManagement().WindowsInformationProtectionPolicies().ByWindowsInformationProtectionPolicieId("windowsInformationProtectionPolicy-id").ExemptAppLockerFiles().ByExemptAppLockerFileId("windowsInformationProtectionAppLockerFile-id").Get(context.Background(), nil)


```