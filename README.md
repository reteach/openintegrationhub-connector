# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p>
# <p align="center" width="100%"> reteach Rest API Documentation OIH Connector </p>

## Description

A generated OIH connector for the reteach Rest API Documentation API (version 1.0).

Generated from: https://api.reteach.io/docs-json<br/>
Generated at: 2022-12-09T17:10:37+01:00

## API Description

This document describes all endpoints of the reteach Rest API. To use them, you have to <a href="https://www.notion.so/reteach/REST-API-Access-and-Authentication-eb420cb4a8474b77a6527d19e7db00f2" taget="_blank">obtain a bearer token</a> for your reteach account.<br/>
      The OpenAPI Specification of the API can be found <a href="https://api.reteach.io/docs-json" taget="_blank">here</a>.<br/>

## Authorization

Supported authorization schemes:
- Bearer Token

## Actions

### Updates a single tag

*Tags:* `Tag`

#### Input Parameters
* `tagIdOrName` - _required_ - Either the id or the name of the tag<br/>

### Triggers an email invitation for a customer

*Tags:* `Customer`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

### Retrieves a single e-commerce order

*Tags:* `Order`

#### Input Parameters
* `orderId` - _required_ - The id of the e-commerce order<br/>

### Finds or creates a single customer

*Tags:* `Customer`

### Creates a single course

*Tags:* `Course`

### Retrieves a single course

*Tags:* `Course`

#### Input Parameters
* `courseId` - _required_ - The id of the course<br/>

### Retrieves a single participation

*Tags:* `Participation`

#### Input Parameters
* `participationId` - _required_ - The id of the participation<br/>

### Assigns a customer to a tag and creates the tag if it does not exist

*Tags:* `Tag`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

### Deletes a single tag

*Tags:* `Tag`

#### Input Parameters
* `tagIdOrName` - _required_ - Either the id or the name of the tag<br/>

### Removes a tag from a customer by customerIdentifier (id, email, or username) and tag

*Tags:* `Tag`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>
* `tagIdOrName` - _required_ - Either the id or the name of the tag<br/>

### Creates a single customer export

*Tags:* `CustomerExport`

### Triggers an email course invitation for a customer

*Tags:* `Participation`

#### Input Parameters
* `participationId` - _required_ - The id of the participation<br/>

### Assigns multiple tags to a customer. Tags will be created if they do not exist.

*Tags:* `Tag`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

### Retrieves a single webhook by id

*Tags:* `Webhook`

#### Input Parameters
* `subscriptionId` - _required_ - The id of the subscription<br/>

### Deletes a single webhook by id

*Tags:* `Webhook`

#### Input Parameters
* `subscriptionId` - _required_ - The id of the subscription<br/>

### Creates a webhook

*Tags:* `Webhook`

### Retrieves a single course invitation

*Tags:* `CourseInvitation`

#### Input Parameters
* `courseInvitationId` - _required_ - The id of the course invitation<br/>

### Finds or creates a single tag

*Tags:* `Tag`

### Creates a single course invitation

*Tags:* `CourseInvitation`

### Retrieves a single customer export by id

*Tags:* `CustomerExport`

#### Input Parameters
* `customerExportId` - _required_ - The id of the customer export<br/>

### Retrieves a single customer group

*Tags:* `CustomerGroup`

#### Input Parameters
* `customerGroupId` - _required_ - The id of the customer group<br/>

### Triggers an email course invitation for an invitation

*Tags:* `CourseInvitation`

#### Input Parameters
* `courseInvitationId` - _required_ - The id of the course invitation<br/>

### Updates a single customer

*Tags:* `Customer`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

### Deletes a single customer group

*Tags:* `CustomerGroup`

#### Input Parameters
* `customerGroupId` - _required_ - The id of the customer group<br/>

### Deletes a single course invitation

*Tags:* `CourseInvitation`

#### Input Parameters
* `courseInvitationId` - _required_ - The id of the course invitation<br/>

### Creates a single customer group

*Tags:* `CustomerGroup`

### Removes a single customer

*Tags:* `Customer`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

### Retrieves a single customer

*Tags:* `Customer`

#### Input Parameters
* `customerIdentifier` - _required_ - Either the id, the email, or the username of the customer<br/>

## License

: reteach<br/>
                    <br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
