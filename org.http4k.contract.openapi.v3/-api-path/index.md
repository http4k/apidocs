[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [ApiPath](./index.md)

# ApiPath

`sealed class ApiPath<NODE>`

### Types

| Name | Summary |
|---|---|
| [NoBody](-no-body/index.md) | `class NoBody<NODE> : `[`ApiPath`](./index.md)`<NODE>` |
| [WithBody](-with-body/index.md) | `class WithBody<NODE> : `[`ApiPath`](./index.md)`<NODE>` |

### Properties

| Name | Summary |
|---|---|
| [deprecated](deprecated.md) | `val deprecated: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [operationId](operation-id.md) | `val operationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parameters](parameters.md) | `val parameters: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RequestParameter`](../-request-parameter/index.md)`<NODE>>` |
| [responses](responses.md) | `val responses: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ResponseContents`](../-response-contents/index.md)`<NODE>>` |
| [security](security.md) | `val security: NODE` |
| [summary](summary.md) | `val summary: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tags](tags.md) | `val tags: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [definitions](definitions.md) | `open fun definitions(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, NODE>>` |
