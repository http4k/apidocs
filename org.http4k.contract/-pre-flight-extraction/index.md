[http4k](../../index.md) / [org.http4k.contract](../index.md) / [PreFlightExtraction](./index.md)

# PreFlightExtraction

`interface PreFlightExtraction : (`[`RouteMeta`](../-route-meta/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>`

### Companion Object Properties

| Name | Summary |
|---|---|
| [All](-all.md) | Check the entire contract, including extracting the body, before passing it to the underlying HttpHandler.`val All: <ERROR CLASS>` |
| [IgnoreBody](-ignore-body.md) | Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times.`val IgnoreBody: <ERROR CLASS>` |
| [None](-none.md) | Check none the contract, relying entirely  on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to fully optimise performance, at the risk of not checking`val None: <ERROR CLASS>` |
