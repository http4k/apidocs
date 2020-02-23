[http4k](../index.md) / [org.http4k.contract.security](./index.md)

## Package org.http4k.contract.security

### Types

| Name | Summary |
|---|---|
| [ApiKeySecurity](-api-key-security/index.md) | Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.`class ApiKeySecurity<out T> : `[`Security`](-security/index.md) |
| [AuthCodeOAuthSecurity](-auth-code-o-auth-security/index.md) | `class AuthCodeOAuthSecurity : `[`OAuthSecurity`](-o-auth-security/index.md) |
| [BasicAuthSecurity](-basic-auth-security/index.md) | Checks the presence of basic auth credentials. Filter returns 401 if auth fails.`class BasicAuthSecurity : `[`Security`](-security/index.md) |
| [BearerAuthSecurity](-bearer-auth-security/index.md) | Checks the presence of bearer auth credentials. Filter returns 401 if auth fails.`class BearerAuthSecurity : `[`Security`](-security/index.md) |
| [ImplicitOAuthSecurity](-implicit-o-auth-security/index.md) | `class ImplicitOAuthSecurity : `[`OAuthSecurity`](-o-auth-security/index.md) |
| [NoSecurity](-no-security/index.md) | Default NoOp security filter. Filter allows all traffic through.`object NoSecurity : `[`Security`](-security/index.md) |
| [OAuthScope](-o-auth-scope/index.md) | `data class OAuthScope` |
| [OAuthSecurity](-o-auth-security/index.md) | `sealed class OAuthSecurity : `[`Security`](-security/index.md) |
| [Security](-security/index.md) | Endpoint security. Provides filter to be applied to endpoints for all requests.`interface Security` |

### Functions

| Name | Summary |
|---|---|
| [and](and.md) | `fun `[`Security`](-security/index.md)`.and(that: `[`Security`](-security/index.md)`): `[`Security`](-security/index.md) |
| [OAuthSecurity](-o-auth-security.md) | `fun ~~OAuthSecurity~~(authorizationUrl: `[`Uri`](../org.http4k.core/-uri/index.md)`, tokenUrl: `[`Uri`](../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OAuthScope`](-o-auth-scope/index.md)`> = emptyList(), filter: `[`Filter`](../org.http4k.core/-filter/index.md)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "oauthSecurity"): `[`AuthCodeOAuthSecurity`](-auth-code-o-auth-security/index.md) |
| [or](or.md) | `fun `[`Security`](-security/index.md)`.or(that: `[`Security`](-security/index.md)`): `[`Security`](-security/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [googleCloudEndpoints](google-cloud-endpoints.md) | `fun OAuthSecurity.Companion.googleCloudEndpoints(issuer: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, jwksUri: `[`Uri`](../org.http4k.core/-uri/index.md)`, audiences: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`ImplicitOAuthSecurity`](-implicit-o-auth-security/index.md) |
