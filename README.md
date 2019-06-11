# ![LOGO](logo.png) PolicyClient **flow**ground Connector

## Description

A generated **flow**ground connector for the PolicyClient API (version 2018-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-policyDefinitions/2018-05-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:13+03:00

## API Description

To manage and control access to your resources, you can define customized policies and assign them at a scope.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve built-in policy definitions

> This operation retrieves a list of all the built-in policy definitions.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.

### Retrieves a built-in policy definition.

> This operation retrieves the built-in policy definition with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the built-in policy definition to get.
* `api-version` - _required_ - The API version to use for the operation.

### Retrieve policy definitions in a management group

> This operation retrieves a list of all the policy definitions in a given management group.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Deletes a policy definition in a management group.

> This operation deletes the policy definition in the given management group with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to delete.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Retrieve a policy definition in a management group.

> This operation retrieves the policy definition in the given management group with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to get.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Creates or updates a policy definition in a management group.

> This operation creates or updates a policy definition in the given management group with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to create.
* `api-version` - _required_ - The API version to use for the operation.
* `managementGroupId` - _required_ - The ID of the management group.

### Retrieves policy definitions in a subscription

> This operation retrieves a list of all the policy definitions in a given subscription.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Deletes a policy definition in a subscription.

> This operation deletes the policy definition in the given subscription with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to delete.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Retrieves a policy definition in a subscription.

> This operation retrieves the policy definition in the given subscription with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to get.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

### Creates or updates a policy definition in a subscription.

> This operation creates or updates a policy definition in the given subscription with the given name.

*Tags:* `PolicyDefinitions`

#### Input Parameters
* `policyDefinitionName` - _required_ - The name of the policy definition to create.
* `api-version` - _required_ - The API version to use for the operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-policy-definitions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
