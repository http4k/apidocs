[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteMeta](./index.md)

# RouteMeta

`data class RouteMeta` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L122)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RouteMeta(summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "<unknown>", description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, tags: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Tag`](../-tag/index.md)`> = emptySet(), body: `[`BodyLens`](../../org.http4k.lens/-body-lens/index.md)`<*>? = null, produces: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`> = emptySet(), consumes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`> = emptySet(), requestParams: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>> = emptyList(), requests: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>> = emptyList(), responses: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>> = emptyList(), preFlightExtraction: `[`PreFlightExtraction`](../-pre-flight-extraction/index.md)`? = null, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`BodyLens`](../../org.http4k.lens/-body-lens/index.md)`<*>?` |
| [consumes](consumes.md) | `val consumes: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [operationId](operation-id.md) | `val operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [preFlightExtraction](pre-flight-extraction.md) | `val preFlightExtraction: `[`PreFlightExtraction`](../-pre-flight-extraction/index.md)`?` |
| [produces](produces.md) | `val produces: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`ContentType`](../../org.http4k.core/-content-type/index.md)`>` |
| [requestParams](request-params.md) | `val requestParams: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` |
| [requests](requests.md) | `val requests: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>>` |
| [responses](responses.md) | `val responses: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>>` |
| [security](security.md) | `val security: `[`Security`](../../org.http4k.contract.security/-security/index.md) |
| [summary](summary.md) | `val summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tags](tags.md) | `val tags: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Tag`](../-tag/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
