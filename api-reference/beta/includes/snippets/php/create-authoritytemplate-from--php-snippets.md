---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new AuthorityTemplate();
$requestBody->setOdataType('#microsoft.graph.security.authorityTemplate');

$requestBody->setDisplayName('String');

$createdBy = new IdentitySet();
$createdBy->setOdataType('microsoft.graph.identitySet');


$requestBody->setCreatedBy($createdBy);


$result = $graphServiceClient->security()->labels()->authorities()->post($requestBody);


```