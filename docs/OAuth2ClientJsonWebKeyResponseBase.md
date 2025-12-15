# Okta.Sdk.Model.OAuth2ClientJsonWebKeyResponseBase
A [JSON Web Key (JWK)](https://tools.ietf.org/html/rfc7517) is a JSON representation of a cryptographic key used by an OAuth 2.0 client.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **string** | Timestamp when the OAuth 2.0 client JSON Web Key was created | [optional] [readonly] 
**Id** | **string** | The unique ID of the OAuth Client JSON Web Key | [optional] [readonly] 
**LastUpdated** | **string** | Timestamp when the OAuth 2.0 client JSON Web Key was updated | [optional] [readonly] 
**Kty** | **string** | Cryptographic algorithm family for the certificate&#39;s key pair | [optional] 
**Status** | **string** | Status of the OAuth 2.0 client JSON Web Key | [optional] [default to StatusEnum.ACTIVE]
**Kid** | **string** | Unique identifier of the JSON Web Key in the OAuth 2.0 client&#39;s JWKS | [optional] 
**Use** | **string** | Acceptable use of the JSON Web Key | [optional] 
**Links** | [**OAuthClientSecretLinks**](OAuthClientSecretLinks.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

