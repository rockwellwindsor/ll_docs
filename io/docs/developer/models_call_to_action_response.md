# Call to Action Response

The *Call to Action Response* class is responsible for creating the responses to the call to action forms, "leads", on the site.

## Attributes

The *Call to Action Response* object has 13 attributes:

  * Name: <b>response date</b>, Type: <b>DateTime</b>
    * The date the reponse comes in.
  * Name: <b>name</b>, Type: <b>String</b>
    * The name entered by the individual filling out the form.
  * Name: <b>target url</b>, Type: <b>String</b>
    * 
  * Name: <b>page url</b>, Type: <b>String</b>
    * The URL of the page the form is on.
  * Name: <b>page version</b>, Type: <b>String</b>
    * The version of the page the form is on.
  * Name: <b>template response path base</b>, Type: <b>String</b>
    * 
  * Name: <b>email</b>, Type: <b>String</b>
    * The email entered in by the individul filling out the form.
  * Name: <b>campaign source</b>, Type: <b>String</b>
    * 
  * Name: <b>campaign medium</b>, Type: <b>String</b>
    * 
  * Name: <b>campaign name</b>, Type: <b>String</b>
    * 
  * Name: <b>campaign content</b>, Type: <b>String</b>
    * 
  * Name: <b>campaign term</b>, Type: <b>String</b>
    * 
  * Name: <b>lead data</b>, Type: <b>String</b>
    * 

## Associations

The *Call to Action Response* has 2 associations.

  * A *Call to Action Response* is _embedded_in_ a <a href="/developer/models_lead">lead</a>.
  * A *Call to Action Response* _belongs_to_ a <a href="/developer/models_page">page</a>.

## Validations

The *Call to Action Response* object has no validations.

## Example

