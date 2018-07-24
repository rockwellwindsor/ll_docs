# Action

The *ACTION* class represents an object that is an action assigned and available to a certain role a <a href="/developer/models_user">User</a> can have.

The *ACTION* objects for the site are all created in the app/db/seed.rb file.

## Attributes

The *Action* object has two attributes:

  * Name: <b>key</b>, Type: <b>String</b>
    * The _key_ attribute provides a name for the action.
  * Name: <b>description</b>, Type: <b>String</b>
    * The _description_ attribute describes the action.

## Associations

The *Action* object has a _belongs_to_and_has_many_ relationship with <a href="/developer/models_role">Roles</a>.

## Validations

The *Action* object does not have any validations.

## Example

`[#<Action _id: 5aa15c8bbc1c62f9eb000004, key: "manage_users", description: "Manage Users", role_ids: ["XXXXXxxxXXxxxXxXXXXXX"]>]`
