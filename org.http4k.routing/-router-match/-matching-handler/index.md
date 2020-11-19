[http4k](../../../index.md) / [org.http4k.routing](../../index.md) / [RouterMatch](../index.md) / [MatchingHandler](./index.md)

# MatchingHandler

`data class MatchingHandler : `[`RouterMatch`](../index.md)`, `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MatchingHandler(httpHandler: `[`HttpHandler`](../../../org.http4k.core/-http-handler.md)`, description: `[`RouterDescription`](../../-router-description/index.md)`, subMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`> = listOf())` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`RouterDescription`](../../-router-description/index.md) |
| [subMatches](sub-matches.md) | `val subMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [aggregatedBy](aggregated-by.md) | `fun aggregatedBy(description: `[`RouterDescription`](../../-router-description/index.md)`, fromMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`>): `[`RouterMatch`](../index.md) |
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../../org.http4k.core/-request/index.md)`): `[`Response`](../../../org.http4k.core/-response/index.md) |
