# ![LOGO](logo.png) groupalarm RBAC API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm RBAC API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/rbac<br/>
Generated at: 2019-07-26T13:59:35+03:00

## API Description

The RBAC service implements a role based access control infrastructure to GroupAlarm.com<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### PersonalAccessTokenList
> Lists all personal access tokens created by the current user<br/>

*Tags:* `personal-access-token`

### PersonalAccessTokenCreate
> Creates a new personal access token for the current user<br/>

*Tags:* `personal-access-token`

### PersonalAccessTokenRegenerate
> Regenerates an existing personal access token for the current user<br/>

*Tags:* `personal-access-token`

#### Input Parameters
* `id` - _required_

### PersonalAccessTokenDelete
> Deletes the given personal access tokens<br/>

*Tags:* `personal-access-token`

#### Input Parameters
* `id` - _required_

### RoleList
> Returns all roles with passed organization id<br/>

*Tags:* `roles`

#### Input Parameters
* `organization_id` - _required_

### RoleCreate
> Creates a new role in passed organization id<br/>

*Tags:* `roles`

### RoleGet
> Get specific role with passed ID<br/>

*Tags:* `roles`

#### Input Parameters
* `roleID` - _required_

### RoleDelete
> Delete specific role with passed ID<br/>

*Tags:* `roles`

#### Input Parameters
* `roleID` - _required_

### RoleUpdate
> Update specific role with passed ID<br/>

*Tags:* `roles`

#### Input Parameters
* `roleID` - _required_

### RoleAccessList
> List all assigned accesses for the passed roleID<br/>

*Tags:* `roleaccess`

#### Input Parameters
* `roleID` - _required_

### RoleAccessCreate
> Creates a role access definition<br/>

*Tags:* `roleaccess`

#### Input Parameters
* `roleID` - _required_

### RoleAccessDelete
> Creates an role access definition<br/>

*Tags:* `roleaccess`

#### Input Parameters
* `roleID` - _required_
* `roleAccessID` - _required_

### RoleAccessUpdate
> Updates a role access definition<br/>

*Tags:* `roleaccess`

#### Input Parameters
* `roleID` - _required_
* `roleAccessID` - _required_

### UserRoleList
> List all assigned user for passed roleID<br/>

*Tags:* `userroles`

#### Input Parameters
* `roleID` - _required_

### UserRoleCreate
> Create a user to role assignment<br/>

*Tags:* `userroles`

#### Input Parameters
* `roleID` - _required_

### DeleteUserRole
> Deletes an user-role assignment for the passed IDs<br/>

*Tags:* `userroles`

#### Input Parameters
* `roleID` - _required_
* `userID` - _required_

### ServicesList
> List all up and running services from GroupAlarm.com<br/>

*Tags:* `services`

### GetUserRoles
> Returns all roles for the current logged in user (JWT-TOKEN)<br/>

*Tags:* `userroles`

## License

**flow**ground :- Telekom iPaaS / groupalarm-rbac-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
