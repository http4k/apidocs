[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [ApiKeySecurity](./index.md)

# ApiKeySecurity

`class ApiKeySecurity<out T> : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/security/ApiKeySecurity.kt#L17)

Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.

Default implementation of ApiKey. Includes an option to NOT authorise OPTIONS requests, which is
currently not enabled for OpenAPI.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApiKeySecurity(param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](index.md#T)`>, validateKey: (`[`T`](index.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, authorizeOptionsRequests: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "api_key")`<br>Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request. |

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [param](param.md) | `val param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](index.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Companion Object Extension Properties

| Name | Summary |
|---|---|
| [renderer](../../org.http4k.contract.openapi.v2/renderer.md) | `val ApiKeySecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
| [renderer](../../org.http4k.contract.openapi.v3/renderer.md) | `val ApiKeySecurity.Companion.renderer: `[`SecurityRenderer`](../../org.http4k.contract.openapi/-security-renderer/index.md) |
