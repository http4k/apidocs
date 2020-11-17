[http4k](../../index.md) / [org.http4k.graphql](../index.md) / [GraphQLResponse](./index.md)

# GraphQLResponse

`data class GraphQLResponse`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GraphQLResponse(data: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?, errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>>?)` |

### Properties

| Name | Summary |
|---|---|
| [data](data.md) | `val data: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [errors](errors.md) | `val errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>>?` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [responseLens](response-lens.md) | `val responseLens: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`GraphQLResponse`](./index.md)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(executionResult: ExecutionResult): `[`GraphQLResponse`](./index.md) |
