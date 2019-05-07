# ![LOGO](logo.png) posty_API **flow**ground Connector

## Description

A generated **flow**ground connector for the posty_API API (version v1).

Generated from: https://api.apis.guru/v2/specs/posty-api.herokuapp.com/v1/swagger.json<br/>
Generated at: 2019-05-07T17:43:45+03:00

## API Description

The posty_API is the core element of the posty softwarestack. It is developed to administrate a mailserver based on Postfix and Dovecot. It offers an easy REST interface which can be used in own applications or with the posty client applications, posty_CLI and posty_webUI.

## Authorization

This API does not require authorization.

## Actions

### Returns all available domains

*Tags:* `domains`

### Create new domain

*Tags:* `domains`

### Delete the specified domain

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Returns the information to the specified domain

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Update the specified domain

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Returns all aliases for the specified domain

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Create new domain alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Delete the specified domain alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `alias_name` - _required_

### Returns the information to the specified domain alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `alias_name` - _required_

### Update the specified domain alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `alias_name` - _required_

### Returns all users for the specified domain

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Create new user

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_

### Delete the specified user

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_

### Returns the information to the specified user

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_

### Update the specified user

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_

### Returns all aliases for the specified user

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_

### Create new user alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_

### Delete the specified user alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_
* `alias_name` - _required_

### Returns the information to the specified user alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_
* `alias_name` - _required_

### Update the specified user alias

*Tags:* `domains`

#### Input Parameters
* `domain_name` - _required_
* `user_name` - _required_
* `alias_name` - _required_

### Returns a summary of all Resources

*Tags:* `summary`

### Swagger compatible API description

*Tags:* `v1`

### Swagger compatible API description for specific API

*Tags:* `v1`

#### Input Parameters
* `name` - _required_ - Resource name of mounted API

### Returns all available transports

*Tags:* `transports`

### Create new transport

*Tags:* `transports`

### Delete the specified transport

*Tags:* `transports`

#### Input Parameters
* `transport_name` - _required_

### Returns the information to the specified transport

*Tags:* `transports`

#### Input Parameters
* `transport_name` - _required_

### Update the specified transport

*Tags:* `transports`

#### Input Parameters
* `transport_name` - _required_

## License

**flow**ground :- Telekom iPaaS / posty-api-herokuapp-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
