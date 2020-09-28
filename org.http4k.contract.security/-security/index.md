[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [Security](./index.md)

# Security

`interface Security`

Endpoint security. Provides filter to be applied to endpoints for all requests.

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `abstract val filter: `[`Filter`](../../org.http4k.core/-filter.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../and.md) | `fun `[`Security`](./index.md)`.and(that: `[`Security`](./index.md)`): `[`Security`](./index.md) |
| [or](../or.md) | `fun `[`Security`](./index.md)`.or(that: `[`Security`](./index.md)`): `[`Security`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ApiKeySecurity](../-api-key-security/index.md) | Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.`class ApiKeySecurity<out T> : `[`Security`](./index.md) |
| [BasicAuthSecurity](../-basic-auth-security/index.md) | Checks the presence of basic auth credentials. Filter returns 401 if auth fails.`class BasicAuthSecurity : `[`Security`](./index.md) |
| [BearerAuthSecurity](../-bearer-auth-security/index.md) | Checks the presence of bearer auth credentials. Filter returns 401 if auth fails.`class BearerAuthSecurity : `[`Security`](./index.md) |
| [NoSecurity](../-no-security/index.md) | Default NoOp security filter. Filter allows all traffic through.`object NoSecurity : `[`Security`](./index.md) |
| [OAuthSecurity](../-o-auth-security/index.md) | `sealed class OAuthSecurity : `[`Security`](./index.md) |
