[http4k](../../index.md) / [org.http4k.graphql](../index.md) / [GraphQLRequest](./index.md)

# GraphQLRequest

`data class GraphQLRequest`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GraphQLRequest(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", operationName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, variables: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> = emptyMap())` |

### Properties

| Name | Summary |
|---|---|
| [operationName](operation-name.md) | `val operationName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [query](query.md) | `val query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [variables](variables.md) | `val variables: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [requestLens](request-lens.md) | `val requestLens: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`GraphQLRequest`](./index.md)`>` |
