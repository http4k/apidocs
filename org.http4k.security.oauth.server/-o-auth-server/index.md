[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [OAuthServer](./index.md)

# OAuthServer

`class OAuthServer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/OAuthServer.kt#L31)

Provide help creating OAuth Authorization Server with Authorization Code Flow

References:

* Authorization Code Grant flow spec: https://tools.ietf.org/html/rfc6749#page-23
* OAuth 2 Security Best Current Practices: https://tools.ietf.org/html/draft-ietf-oauth-security-topics-11

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthServer(tokenPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authRequestTracking: `[`AuthRequestTracking`](../-auth-request-tracking/index.md)`, clientValidator: `[`ClientValidator`](../-client-validator/index.md)`, authorizationCodes: `[`AuthorizationCodes`](../-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../-access-tokens/index.md)`, json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)`, authRequestExtractor: `[`AuthRequestExtractor`](../-auth-request-extractor/index.md)` = AuthRequestFromQueryParameters, grantTypes: `[`GrantTypesConfiguration`](../../org.http4k.security.oauth.server.accesstoken/-grant-types-configuration/index.md)` = GrantTypesConfiguration.default(ClientSecretAccessTokenRequestAuthentication(clientValidator)), idTokens: `[`IdTokens`](../-id-tokens/index.md)` = IdTokens.Unsupported, documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)``OAuthServer(tokenPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authRequestTracking: `[`AuthRequestTracking`](../-auth-request-tracking/index.md)`, authoriseRequestValidator: `[`AuthoriseRequestValidator`](../-authorise-request-validator/index.md)`, accessTokenRequestAuthentication: `[`AccessTokenRequestAuthentication`](../../org.http4k.security.oauth.server.accesstoken/-access-token-request-authentication/index.md)`, authorizationCodes: `[`AuthorizationCodes`](../-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../-access-tokens/index.md)`, json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)`, authRequestExtractor: `[`AuthRequestExtractor`](../-auth-request-extractor/index.md)` = AuthRequestFromQueryParameters, grantTypes: `[`GrantTypesConfiguration`](../../org.http4k.security.oauth.server.accesstoken/-grant-types-configuration/index.md)` = GrantTypesConfiguration.default(accessTokenRequestAuthentication), idTokens: `[`IdTokens`](../-id-tokens/index.md)` = IdTokens.Unsupported, documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)`<br>Provide help creating OAuth Authorization Server with Authorization Code Flow |

### Properties

| Name | Summary |
|---|---|
| [authenticationComplete](authentication-complete.md) | `val authenticationComplete: `[`AuthenticationComplete`](../-authentication-complete/index.md) |
| [authenticationStart](authentication-start.md) | `val authenticationStart: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [tokenRoute](token-route.md) | `val tokenRoute: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [clientAssertion](client-assertion.md) | `val clientAssertion: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [clientAssertionType](client-assertion-type.md) | `val clientAssertionType: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`?>` |
| [clientIdForm](client-id-form.md) | `val clientIdForm: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`ClientId`](../-client-id/index.md)`?>` |
| [clientIdQueryParameter](client-id-query-parameter.md) | `val clientIdQueryParameter: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ClientId`](../-client-id/index.md)`>` |
| [clientSecret](client-secret.md) | `val clientSecret: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [nonce](nonce.md) | `val nonce: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [redirectUri](redirect-uri.md) | `val redirectUri: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Uri`](../../org.http4k.core/-uri/index.md)`>` |
| [request](request.md) | `val request: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`RequestJwtContainer`](../../org.http4k.security.openid/-request-jwt-container/index.md)`?>` |
| [responseType](response-type.md) | `val responseType: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ResponseType`](../../org.http4k.security/-response-type/index.md)`>` |
| [scopesForm](scopes-form.md) | `val scopesForm: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?>` |
| [scopesQueryParameter](scopes-query-parameter.md) | `val scopesQueryParameter: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?>` |
| [state](state.md) | `val state: `[`BiDiLens`](../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [tokenRequestWebForm](token-request-web-form.md) | `val tokenRequestWebForm: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`WebForm`](../../org.http4k.lens/-web-form/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
