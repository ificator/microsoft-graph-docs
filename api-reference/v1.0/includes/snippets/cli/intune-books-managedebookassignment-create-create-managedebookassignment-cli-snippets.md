---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-app-management managed-ebooks assignments create --managed-ebook-id {managedEBook-id} --body '{\
  "@odata.type": "#microsoft.graph.managedEBookAssignment",\
  "target": {\
    "@odata.type": "microsoft.graph.allLicensedUsersAssignmentTarget"\
  },\
  "installIntent": "required"\
}\
'

```