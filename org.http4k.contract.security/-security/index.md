[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [Security](./index.md)

# Security

`interface Security` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/Security.kt#L8)

Endpoint security. Provides filter to be applied to endpoints for all requests.

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `abstract val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ApiKeySecurity](../-api-key-security/index.md) | `class ApiKeySecurity<out T> : `[`Security`](./index.md)<br>Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request. |
| [BasicAuthSecurity](../-basic-auth-security/index.md) | `class BasicAuthSecurity : `[`Security`](./index.md)<br>Checks the presence of basic auth credentials. Filter returns 401 if auth fails. |
| [BearerAuthSecurity](../-bearer-auth-security/index.md) | `class BearerAuthSecurity : `[`Security`](./index.md)<br>Checks the presence of bearer auth credentials. Filter returns 401 if auth fails. |
| [NoSecurity](../-no-security/index.md) | `object NoSecurity : `[`Security`](./index.md)<br>Default NoOp security filter. Filter allows all traffic through. |
