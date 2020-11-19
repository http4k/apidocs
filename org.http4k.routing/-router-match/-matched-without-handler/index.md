[http4k](../../../index.md) / [org.http4k.routing](../../index.md) / [RouterMatch](../index.md) / [MatchedWithoutHandler](./index.md)

# MatchedWithoutHandler

`data class MatchedWithoutHandler : `[`RouterMatch`](../index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MatchedWithoutHandler(description: `[`RouterDescription`](../../-router-description/index.md)`, subMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`> = listOf())` |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `val description: `[`RouterDescription`](../../-router-description/index.md) |
| [subMatches](sub-matches.md) | `val subMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [aggregatedBy](aggregated-by.md) | `fun aggregatedBy(description: `[`RouterDescription`](../../-router-description/index.md)`, fromMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](../index.md)`>): `[`RouterMatch`](../index.md) |
