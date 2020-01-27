[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionOptions](./index.md)

# InteractionOptions

`interface InteractionOptions` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionOptions.kt#L7)

### Types

| Name | Summary |
|---|---|
| [Defaults](-defaults.md) | `object Defaults : `[`InteractionOptions`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [isBinary](is-binary.md) | `open fun isBinary(contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [requestManipulations](request-manipulations.md) | `open fun requestManipulations(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [responseManipulations](response-manipulations.md) | `open fun responseManipulations(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [Defaults](-defaults.md) | `object Defaults : `[`InteractionOptions`](./index.md) |
