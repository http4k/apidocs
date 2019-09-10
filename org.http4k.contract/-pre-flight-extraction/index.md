[http4k](../../index.md) / [org.http4k.contract](../index.md) / [PreFlightExtraction](./index.md)

# PreFlightExtraction

`interface PreFlightExtraction : (`[`RouteMeta`](../-route-meta/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, *>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/PreFlightExtraction.kt#L17)

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
| [All](-all/index.md) | `object All : `[`PreFlightExtraction`](./index.md)<br>Check the entire contract, including extracting the body, before passing it to the underlying HttpHandler. |
| [IgnoreBody](-ignore-body/index.md) | `object IgnoreBody : `[`PreFlightExtraction`](./index.md)<br>Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times. |
| [None](-none/index.md) | `object None : `[`PreFlightExtraction`](./index.md)<br>Check none the contract, relying entirely  on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to fully optimise performance, at the risk of not checking |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [All](-all/index.md) | `object All : `[`PreFlightExtraction`](./index.md)<br>Check the entire contract, including extracting the body, before passing it to the underlying HttpHandler. |
| [IgnoreBody](-ignore-body/index.md) | `object IgnoreBody : `[`PreFlightExtraction`](./index.md)<br>Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times. |
| [None](-none/index.md) | `object None : `[`PreFlightExtraction`](./index.md)<br>Check none the contract, relying entirely  on the HttpHandler code to raise a correct LensFailure if extraction fails. Use this option to fully optimise performance, at the risk of not checking |
