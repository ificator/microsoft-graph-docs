---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestConfiguration = new WorkflowVersionRequestBuilderGetRequestConfiguration();
$queryParameters = WorkflowVersionRequestBuilderGetRequestConfiguration::createQueryParameters();
$queryParameters->select = ["category","displayName","versionNumber","executionConditions"];
$queryParameters->expand = ["tasks"];
$requestConfiguration->queryParameters = $queryParameters;


$result = $graphServiceClient->identityGovernance()->lifecycleWorkflows()->workflows()->byWorkflowId('workflow-id')->versions()->byWorkflowVersionId('workflowVersion-versionNumber')->get($requestConfiguration);


```