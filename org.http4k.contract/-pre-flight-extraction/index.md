[http4k](../../index.md) / [org.http4k.contract](../index.md) / [PreFlightExtraction](./index.md)

# PreFlightExtraction

`interface PreFlightExtraction : (`[`RouteMeta`](../-route-meta/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>`

Determines which parts of the request should be pre-extracted to check for presence before being passed to the ultimate
HttpHandler for this route. Choice will be determined by two competing scenarios:

1. By selecting a All of the request to be pre-extracted (the default), we can collect all errors at once to be
returned to the client - which is more user friendly. If we fall back on just the Lens usage in the
HttpHandler code, only the first failing Lens extraction will be reported.
2. Not pre-checking parts of the request is more efficient, which may be important given parsing of request
bodies could be expensive and pre-flight-extraction would involve performing this operation twice.

### Types

| Name | Summary |
|---|---|
| [All](-all/index.md) | Check the entire contract, including extracting the body, before passing it to the underlying HttpHandler.`object All : `[`PreFlightExtraction`](./index.md) |
| [IgnoreBody](-ignore-body/index.md) | Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times.`object IgnoreBody : `[`PreFlightExtraction`](./index.md) |
| [None](-none/index.md) | Check none the contract, relying entirely  on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to fully optimise performance, at the risk of not checking`object None : `[`PreFlightExtraction`](./index.md) |
