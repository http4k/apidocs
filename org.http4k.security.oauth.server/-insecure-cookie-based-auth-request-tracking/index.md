[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [InsecureCookieBasedAuthRequestTracking](./index.md)

# InsecureCookieBasedAuthRequestTracking

`class InsecureCookieBasedAuthRequestTracking : `[`AuthRequestTracking`](../-auth-request-tracking/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/InsecureCookieBasedAuthRequestTracking.kt#L7)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsecureCookieBasedAuthRequestTracking()` |

### Functions

| Name | Summary |
|---|---|
| [resolveAuthRequest](resolve-auth-request.md) | `fun resolveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?`<br>Resolves a particular AuthRequest related to the particular request |
| [trackAuthRequest](track-auth-request.md) | `fun trackAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Assign a reference of AuthRequest to the response |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
