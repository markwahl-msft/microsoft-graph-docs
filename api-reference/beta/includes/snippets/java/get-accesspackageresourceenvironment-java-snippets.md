---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

AccessPackageResourceEnvironment accessPackageResourceEnvironment = graphClient.identityGovernance().entitlementManagement().accessPackageResourceEnvironments("{accessPackageResourceEnvironmentId}")
	.buildRequest()
	.get();

```