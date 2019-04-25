[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [OAuthServer](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`OAuthServer(tokenPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authRequestTracking: `[`AuthRequestTracking`](../-auth-request-tracking/index.md)`, clientValidator: `[`ClientValidator`](../-client-validator/index.md)`, authorizationCodes: `[`AuthorizationCodes`](../-authorization-codes/index.md)`, accessTokens: `[`AccessTokens`](../-access-tokens/index.md)`, json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`, clock: Clock, idTokens: `[`IdTokens`](../-id-tokens/index.md)` = IdTokens.Unsupported)`

Provide help creating OAuth Authorization Server with Authorization Code Flow

References:

* Authorization Code Grant flow spec: https://tools.ietf.org/html/rfc6749#page-23
* OAuth 2 Security Best Current Practices: https://tools.ietf.org/html/draft-ietf-oauth-security-topics-11
