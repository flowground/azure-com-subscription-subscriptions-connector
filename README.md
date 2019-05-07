# ![LOGO](logo.png) SubscriptionClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionClient API (version 2018-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/subscription-subscriptions/2018-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:19+03:00

## API Description

Subscription client provides an interface to create and manage Azure subscriptions programmatically.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Creates an Azure subscription

#### Input Parameters
* `billingAccountName` - _required_ - The name of the commerce root billing account.
* `invoiceSectionName` - _required_ - The name of the invoice section.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### Lists all of the available Microsoft.Subscription API operations.

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### Get the status of the pending Microsoft.Subscription API operations.

#### Input Parameters
* `operationId` - _required_ - The operation ID, which can be found from the Location field in the generate recommendation response header.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

## License

**flow**ground :- Telekom iPaaS / azure-com-subscription-subscriptions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
