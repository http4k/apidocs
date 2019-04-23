[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ApiKeySecurity](./index.md)

# ApiKeySecurity

`class ApiKeySecurity<out T> : `[`Security`](../-security/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/Security.kt#L34)

Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.

Default implementation of ApiKey. Includes an option to NOT authorise OPTIONS requests, which is
currently not enabled for OpenAPI.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApiKeySecurity(param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](index.md#T)`>, validateKey: (`[`T`](index.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, authorizeOptionsRequests: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true)`<br>Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request. |

### Properties

| Name | Summary |
|---|---|
| [filter](filter.md) | `val filter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [param](param.md) | `val param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, `[`T`](index.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
