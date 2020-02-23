[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [InsecureCookieBasedAuthRequestTracking](./index.md)

# InsecureCookieBasedAuthRequestTracking

`class InsecureCookieBasedAuthRequestTracking : `[`AuthRequestTracking`](../-auth-request-tracking/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsecureCookieBasedAuthRequestTracking()` |

### Functions

| Name | Summary |
|---|---|
| [resolveAuthRequest](resolve-auth-request.md) | Resolves a particular AuthRequest related to the particular request`fun resolveAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`AuthRequest`](../-auth-request/index.md)`?` |
| [trackAuthRequest](track-auth-request.md) | Assign a reference of AuthRequest to the response`fun trackAuthRequest(request: `[`Request`](../../org.http4k.core/-request/index.md)`, authRequest: `[`AuthRequest`](../-auth-request/index.md)`, response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
