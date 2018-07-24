# API Key

The *API KEY* class is responsible for handling an object that represents an api key for Instagram and Bitly.

## Attributes

The *API KEY* object has two attributes:

  * Name: <b>api name</b>, Type: <b>String</b>
    * The _api_name_ attribute provides a name for the api key.
  * Name: <b>access token</b>, Type: <b>String</b>
    * The _access_token_ attribute describes the action.

## Associations

The *API KEY* object is _embedded_in_ a <a href="/developer/models_site">site</a>.

## Validations

The *API KEY* object has two validations.

  * presence of _api_name_
  * uniqueness of _acess_token_
  
## Example

