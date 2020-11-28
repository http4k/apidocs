[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RouterMatch](./index.md)

# RouterMatch

`sealed class RouterMatch : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`RouterMatch`](./index.md)`>`

The result of a matching operation. May or may not contain a matched HttpHandler.

### Types

| Name | Summary |
|---|---|
| [MatchedWithoutHandler](-matched-without-handler/index.md) | `data class MatchedWithoutHandler : `[`RouterMatch`](./index.md) |
| [MatchingHandler](-matching-handler/index.md) | `data class MatchingHandler : `[`RouterMatch`](./index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [MethodNotMatched](-method-not-matched/index.md) | `data class MethodNotMatched : `[`RouterMatch`](./index.md) |
| [Unmatched](-unmatched/index.md) | `data class Unmatched : `[`RouterMatch`](./index.md) |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `open val description: `[`RouterDescription`](../-router-description/index.md) |
| [subMatches](sub-matches.md) | `open val subMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](./index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [aggregatedBy](aggregated-by.md) | `abstract fun aggregatedBy(description: `[`RouterDescription`](../-router-description/index.md)`, fromMatches: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterMatch`](./index.md)`>): `[`RouterMatch`](./index.md) |
| [compareTo](compare-to.md) | `open fun compareTo(other: `[`RouterMatch`](./index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [prettify](../../org.http4k.routing.inspect/prettify.md) | `fun `[`RouterMatch`](./index.md)`.prettify(depth: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, escape: `[`EscapeMode`](../../org.http4k.routing.inspect/-escape-mode/index.md)` = Ansi): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
