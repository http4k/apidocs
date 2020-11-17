[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RouterMatch](./index.md)

# RouterMatch

`sealed class RouterMatch : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`RouterMatch`](./index.md)`>`

The result of a matching operation. May or may not contain a matched HttpHandler.

### Types

| Name | Summary |
|---|---|
| [MatchedWithoutHandler](-matched-without-handler.md) | `object MatchedWithoutHandler : `[`RouterMatch`](./index.md) |
| [MatchingHandler](-matching-handler/index.md) | `data class MatchingHandler : `[`RouterMatch`](./index.md)`, `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [MethodNotMatched](-method-not-matched.md) | `object MethodNotMatched : `[`RouterMatch`](./index.md) |
| [Unmatched](-unmatched.md) | `object Unmatched : `[`RouterMatch`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | `open fun compareTo(other: `[`RouterMatch`](./index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
