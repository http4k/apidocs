[http4k](../../../index.md) / [org.http4k.contract.openapi.v3](../../index.md) / [ApiPath](../index.md) / [NoBody](./index.md)

# NoBody

`class NoBody<NODE> : `[`ApiPath`](../index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/v3/model.kt#L36)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `NoBody(summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, parameters: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RequestParameter`](../../-request-parameter/index.md)`<`[`NODE`](index.md#NODE)`>>, responses: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ResponseContents`](../../-response-contents/index.md)`<`[`NODE`](index.md#NODE)`>>, security: `[`NODE`](index.md#NODE)`, operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [operationId](../operation-id.md) | `val operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parameters](../parameters.md) | `val parameters: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RequestParameter`](../../-request-parameter/index.md)`<`[`NODE`](../index.md#NODE)`>>` |
| [responses](../responses.md) | `val responses: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ResponseContents`](../../-response-contents/index.md)`<`[`NODE`](../index.md#NODE)`>>` |
| [security](../security.md) | `val security: `[`NODE`](../index.md#NODE) |
| [summary](../summary.md) | `val summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tags](../tags.md) | `val tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [definitions](../definitions.md) | `open fun definitions(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../index.md#NODE)`>>` |
