[http4k](../index.md) / [org.http4k.security.oauth.server](./index.md)

## Package org.http4k.security.oauth.server

### Types

| Name | Summary |
|---|---|
| [AccessTokenError](-access-token-error.md) | `sealed class AccessTokenError : `[`OAuthError`](-o-auth-error/index.md) |
| [AccessTokens](-access-tokens/index.md) | Provides a consistent way to generate access tokens.`interface AccessTokens` |
| [AuthenticationComplete](-authentication-complete/index.md) | `class AuthenticationComplete : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [AuthoriseRequestErrorRender](-authorise-request-error-render/index.md) | `class AuthoriseRequestErrorRender` |
| [AuthoriseRequestValidator](-authorise-request-validator/index.md) | `interface AuthoriseRequestValidator` |
| [AuthorizationCode](-authorization-code/index.md) | `data class AuthorizationCode` |
| [AuthorizationCodeAlreadyUsed](-authorization-code-already-used.md) | `object AuthorizationCodeAlreadyUsed : `[`AccessTokenError`](-access-token-error.md) |
| [AuthorizationCodeDetails](-authorization-code-details/index.md) | `data class AuthorizationCodeDetails` |
| [AuthorizationCodeExpired](-authorization-code-expired.md) | `object AuthorizationCodeExpired : `[`AccessTokenError`](-access-token-error.md) |
| [AuthorizationCodes](-authorization-codes/index.md) | Provides a consistent way to manage authorization codes`interface AuthorizationCodes` |
| [AuthorizationError](-authorization-error.md) | `sealed class AuthorizationError : `[`OAuthError`](-o-auth-error/index.md) |
| [AuthRequest](-auth-request/index.md) | `data class AuthRequest` |
| [AuthRequestExtractor](-auth-request-extractor/index.md) | `interface AuthRequestExtractor` |
| [AuthRequestFromQueryParameters](-auth-request-from-query-parameters/index.md) | `object AuthRequestFromQueryParameters : `[`AuthRequestExtractor`](-auth-request-extractor/index.md) |
| [AuthRequestTracking](-auth-request-tracking/index.md) | Provides a mechanism to track OAuth authorization parameters to be used later (i.e. can be used later to generate code and/or tokens)`interface AuthRequestTracking` |
| [AuthRequestTrackingFilter](-auth-request-tracking-filter/index.md) | `class AuthRequestTrackingFilter : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [AuthRequestWithRequestAuthRequestExtractor](-auth-request-with-request-auth-request-extractor/index.md) | `class AuthRequestWithRequestAuthRequestExtractor : `[`AuthRequestExtractor`](-auth-request-extractor/index.md) |
| [ClientId](-client-id/index.md) | `data class ClientId` |
| [ClientIdMismatch](-client-id-mismatch.md) | `object ClientIdMismatch : `[`AccessTokenError`](-access-token-error.md) |
| [ClientValidationFilter](-client-validation-filter/index.md) | `class ClientValidationFilter : `[`Filter`](../org.http4k.core/-filter/index.md) |
| [ClientValidator](-client-validator/index.md) | Provides a consistent way to retrieve clients attempting to use an authorization code flow`interface ClientValidator` |
| [FragmentResponseRender](-fragment-response-render/index.md) | `class FragmentResponseRender : `[`ResponseRender`](-response-render/index.md) |
| [GenerateAccessToken](-generate-access-token/index.md) | `class GenerateAccessToken : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [IdTokens](-id-tokens/index.md) | `interface IdTokens` |
| [InsecureCookieBasedAuthRequestTracking](-insecure-cookie-based-auth-request-tracking/index.md) | `class InsecureCookieBasedAuthRequestTracking : `[`AuthRequestTracking`](-auth-request-tracking/index.md) |
| [InvalidAuthorizationRequest](-invalid-authorization-request/index.md) | `data class InvalidAuthorizationRequest : `[`AuthorizationError`](-authorization-error.md) |
| [InvalidClientAssertion](-invalid-client-assertion.md) | `object InvalidClientAssertion : `[`AccessTokenError`](-access-token-error.md) |
| [InvalidClientAssertionType](-invalid-client-assertion-type.md) | `object InvalidClientAssertionType : `[`AccessTokenError`](-access-token-error.md) |
| [InvalidClientCredentials](-invalid-client-credentials.md) | `object InvalidClientCredentials : `[`AccessTokenError`](-access-token-error.md) |
| [InvalidClientId](-invalid-client-id.md) | `object InvalidClientId : `[`AuthorizationError`](-authorization-error.md) |
| [InvalidRedirectUri](-invalid-redirect-uri.md) | `object InvalidRedirectUri : `[`AuthorizationError`](-authorization-error.md) |
| [InvalidRequest](-invalid-request/index.md) | `data class InvalidRequest : `[`AccessTokenError`](-access-token-error.md) |
| [InvalidRequestObject](-invalid-request-object.md) | `object InvalidRequestObject : `[`AuthorizationError`](-authorization-error.md) |
| [InvalidScopes](-invalid-scopes.md) | `object InvalidScopes : `[`AuthorizationError`](-authorization-error.md) |
| [JsonResponseErrorRenderer](-json-response-error-renderer/index.md) | `class JsonResponseErrorRenderer` |
| [MissingAuthorizationCode](-missing-authorization-code.md) | `object MissingAuthorizationCode : `[`AccessTokenError`](-access-token-error.md) |
| [MissingRedirectUri](-missing-redirect-uri.md) | `object MissingRedirectUri : `[`AccessTokenError`](-access-token-error.md) |
| [MustHaveRedirectUri](-must-have-redirect-uri/index.md) | `class MustHaveRedirectUri : `[`AuthoriseRequestValidator`](-authorise-request-validator/index.md) |
| [OAuthError](-o-auth-error/index.md) | `abstract class OAuthError` |
| [OAuthServer](-o-auth-server/index.md) | Provide help creating OAuth Authorization Server with Authorization Code Flow`class OAuthServer` |
| [QueryResponseRender](-query-response-render/index.md) | `class QueryResponseRender : `[`ResponseRender`](-response-render/index.md) |
| [RedirectUriMismatch](-redirect-uri-mismatch.md) | `object RedirectUriMismatch : `[`AccessTokenError`](-access-token-error.md) |
| [ResponseRender](-response-render/index.md) | `interface ResponseRender` |
| [RfcError](-rfc-error/index.md) | `enum class RfcError` |
| [SimpleAuthoriseRequestValidator](-simple-authorise-request-validator/index.md) | `class SimpleAuthoriseRequestValidator : `[`AuthoriseRequestValidator`](-authorise-request-validator/index.md) |
| [TokenRequest](-token-request/index.md) | `data class TokenRequest` |
| [UnsupportedGrantType](-unsupported-grant-type/index.md) | `data class UnsupportedGrantType : `[`AccessTokenError`](-access-token-error.md) |
| [UnsupportedResponseType](-unsupported-response-type/index.md) | `data class UnsupportedResponseType : `[`AuthorizationError`](-authorization-error.md) |
| [UserRejectedRequest](-user-rejected-request.md) | `object UserRejectedRequest : `[`AuthorizationError`](-authorization-error.md) |
