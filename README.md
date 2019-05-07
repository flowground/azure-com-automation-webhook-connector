# ![LOGO](logo.png) AutomationManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagementClient API (version 2015-10-31).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-webhook/2015-10-31/swagger.json<br/>
Generated at: 2019-05-07T17:37:23+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of webhooks.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `$filter` - _optional_ - The filter to apply on the operation.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Generates a Uri for use in creating a webhook.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Delete the webhook by name.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `webhookName` - _required_ - The webhook name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve the webhook identified by webhook name.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `webhookName` - _required_ - The webhook name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Update the webhook identified by webhook name.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `webhookName` - _required_ - The webhook name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Create the webhook identified by webhook name.

*Tags:* `Webhook`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `webhookName` - _required_ - The webhook name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-webhook-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
