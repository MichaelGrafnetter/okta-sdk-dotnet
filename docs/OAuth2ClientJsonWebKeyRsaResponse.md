# Okta.Sdk.Model.OAuth2ClientJsonWebKeyRsaResponse
An RSA signing key

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **string** | Timestamp when the OAuth 2.0 client JSON Web Key was created | [optional] [readonly] 
**Id** | **string** | The unique ID of the OAuth Client JSON Web Key | [optional] [readonly] 
**LastUpdated** | **string** | Timestamp when the OAuth 2.0 client JSON Web Key was updated | [optional] [readonly] 
**Kty** | **string** | Cryptographic algorithm family for the certificate&#39;s key pair | 
**Status** | **string** | Status of the OAuth 2.0 client JSON Web Key | [optional] [default to StatusEnum.ACTIVE]
**Kid** | **string** | Unique identifier of the JSON Web Key in the OAuth 2.0 client&#39;s JWKS | [optional] 
**Use** | **string** | Acceptable use of the JSON Web Key | [optional] 
**Links** | [**OAuthClientSecretLinks**](OAuthClientSecretLinks.md) |  | [optional] 
**E** | **string** | RSA key value (exponent) for key binding | [optional] 
**N** | **string** | RSA key value (modulus) for key binding | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

