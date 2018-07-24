# Account

The *ACCOUNT* class represents an object which is named and can have multiple <a href="/developer/models_site">sites</a> associated to it.

## Attributes

The *Account* object has 1 attribute:

  * Name: <b>name</b>, Type: <b>String</b>
      * The _name_ attribute provides a name to the account.

## Associations

The *Account* object _has_many_ <a href="/developer/models_site" >sites</a> that can belong to it.

## Validations

The *Account* object has 2 validations:

  * presence of _name_
  * uniqueness of _name_

## Example

An example *Account* object would look like:

  * `[#<Account _id: 5aa1609abc1c626080000001, name: "Sample Account">]`

Example of related <a href="/developer/models_site" >Site</a> record:

  * `[<Site _id: 5af30ac6bc1c620b1c000001, name: "new-site", domains: [], admin_subdomain: "new-site", new_lead_email: "", time_zone: "UTC", min_number_of_versions_to_keep: 25, max_time_to_keep_versions: 2592000, archived: false, public: false, campaign_mediums: nil, not_found_page: nil, account_id: "5aa1609abc1c626080000001", has_members: false>, #<Site _id: 5aa161f1bc1c622f72000005, name: "site", domains: [], admin_subdomain: "site", new_lead_email: "sampleuser@yahoo.com, sampleuser@gmail.com", time_zone: "UTC", min_number_of_versions_to_keep: 25, max_time_to_keep_versions: 2592000, archived: false, public: true, campaign_mediums: nil, not_found_page: nil, account_id: "5aa1609abc1c626080000001", has_members: true>]]`

