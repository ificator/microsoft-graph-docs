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



result, err := graphClient.DeviceManagement().RoleDefinitions().ByRoleDefinitionId("roleDefinition-id").RoleAssignments().ByRoleAssignmentId("roleAssignment-id").Get(context.Background(), nil)


```