# ![LOGO](logo.png) ContainerServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerServiceClient API (version 2017-09-30).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerservices-location/2017-09-30/swagger.json<br/>
Generated at: 2019-05-07T17:37:53+03:00

## API Description

The Container Service Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of supported orchestrators in the specified subscription.

> Gets a list of supported orchestrators in the specified subscription. The operation returns properties of each orchestrator including version and available upgrades.

*Tags:* `ContainerServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - The name of a supported Azure region.
* `resource-type` - _optional_ - resource type for which the list of orchestrators needs to be returned

## License

**flow**ground :- Telekom iPaaS / azure-com-containerservices-location-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
