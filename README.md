# ![LOGO](logo.png) Mixed Reality **flow**ground Connector

## Description

A generated **flow**ground connector for the Mixed Reality API (version 2019-02-28-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/mixedreality/2019-02-28-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:24+03:00

## API Description

Mixed Reality Resource Provider REST API

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Exposing Available Operations

*Tags:* `Proxy`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Check Name Availability for global uniqueness

*Tags:* `Proxy`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `location` - _required_ - The location in which uniqueness will be verified.
* `api-version` - _required_ - Version of the API to be used with the client request.

### List Spatial Anchors Accounts by Subscription

*Tags:* `Resource` `Proxy`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `api-version` - _required_ - Version of the API to be used with the client request.

### List Resources by Resource Group

*Tags:* `Resource`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete a Spatial Anchors Account.

*Tags:* `Resource`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Retrieve a Spatial Anchors Account.

*Tags:* `Resource`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Updating a Spatial Anchors Account

*Tags:* `Resource`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Creating or Updating a Spatial Anchors Account.

*Tags:* `Resource`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get Both of the 2 Keys of a Spatial Anchors Account

*Tags:* `Key`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Regenerate 1 Key of a Spatial Anchors Account

*Tags:* `Key`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Name of an Azure resource group.
* `spatialAnchorsAccountName` - _required_ - Name of an Mixed Reality Spatial Anchors Account.
* `api-version` - _required_ - Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-mixedreality-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
