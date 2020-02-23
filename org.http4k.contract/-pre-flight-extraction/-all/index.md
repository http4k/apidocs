[http4k](../../../index.md) / [org.http4k.contract](../../index.md) / [PreFlightExtraction](../index.md) / [All](./index.md)

# All

`object All : `[`PreFlightExtraction`](../index.md)

Check the entire contract, including extracting the body, before passing it to the underlying
HttpHandler.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(meta: `[`RouteMeta`](../../-route-meta/index.md)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../../org.http4k.core/-request/index.md)`, *>>` |
