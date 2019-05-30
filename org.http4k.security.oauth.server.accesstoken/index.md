[http4k](../index.md) / [org.http4k.security.oauth.server.accesstoken](./index.md)

## Package org.http4k.security.oauth.server.accesstoken

### Types

| Name | Summary |
|---|---|
| [AccessTokenGenerator](-access-token-generator/index.md) | `interface AccessTokenGenerator<T : `[`AccessTokenRequest`](-access-token-request.md)`>` |
| [AccessTokenRequest](-access-token-request.md) | `interface AccessTokenRequest` |
| [AuthorizationCodeAccessTokenGenerator](-authorization-code-access-token-generator/index.md) | `class AuthorizationCodeAccessTokenGenerator : `[`AccessTokenGenerator`](-access-token-generator/index.md)`<`[`AuthorizationCodeAccessTokenRequest`](-authorization-code-access-token-request/index.md)`>` |
| [AuthorizationCodeAccessTokenRequest](-authorization-code-access-token-request/index.md) | `data class AuthorizationCodeAccessTokenRequest : `[`AccessTokenRequest`](-access-token-request.md) |
| [ClientCredentialsAccessTokenGenerator](-client-credentials-access-token-generator/index.md) | `class ClientCredentialsAccessTokenGenerator : `[`AccessTokenGenerator`](-access-token-generator/index.md)`<`[`ClientCredentialsRequest`](-client-credentials-request/index.md)`>` |
| [ClientCredentialsRequest](-client-credentials-request/index.md) | `data class ClientCredentialsRequest : `[`AccessTokenRequest`](-access-token-request.md) |
| [GenerateAccessTokenForGrantType](-generate-access-token-for-grant-type/index.md) | `class GenerateAccessTokenForGrantType` |
