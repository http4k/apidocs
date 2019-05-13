[http4k](../../index.md) / [org.http4k.contract.simple](../index.md) / [SimpleJson](./index.md)

# SimpleJson

`class SimpleJson<out NODE> : `[`ContractRenderer`](../../org.http4k.contract/-contract-renderer/index.md)`, `[`ErrorResponseRenderer`](../../org.http4k.contract/-error-response-renderer/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/simple/SimpleJson.kt#L14)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SimpleJson(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [description](description.md) | `fun description(contractRoot: `[`PathSegments`](../../org.http4k.contract/-path-segments/index.md)`, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)`, routes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ContractRoute`](../../org.http4k.contract/-contract-route/index.md)`>): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |