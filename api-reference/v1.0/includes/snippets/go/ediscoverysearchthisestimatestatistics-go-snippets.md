---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)


graphClient.Security().Cases().EdiscoveryCasesById("ediscoveryCase-id").SearchesById("ediscoverySearch-id").SecurityEstimateStatistics().Post(context.Background(), nil)


```