[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [Api](./index.md)

# Api

`data class Api<NODE>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Api(info: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md)`, tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Tag`](../../org.http4k.contract/-tag/index.md)`>, paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ApiPath`](../-api-path/index.md)`<`[`NODE`](index.md#NODE)`>>>, components: `[`Components`](../-components/index.md)`<`[`NODE`](index.md#NODE)`>)` |

### Properties

| Name | Summary |
|---|---|
| [components](components.md) | `val components: `[`Components`](../-components/index.md)`<`[`NODE`](index.md#NODE)`>` |
| [info](info.md) | `val info: `[`ApiInfo`](../../org.http4k.contract.openapi/-api-info/index.md) |
| [openapi](openapi.md) | `val openapi: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paths](paths.md) | `val paths: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ApiPath`](../-api-path/index.md)`<`[`NODE`](index.md#NODE)`>>>` |
| [tags](tags.md) | `val tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Tag`](../../org.http4k.contract/-tag/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
