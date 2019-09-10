[http4k](../../../index.md) / [org.http4k.contract](../../index.md) / [PreFlightExtraction](../index.md) / [None](./index.md)

# None

`object None : `[`PreFlightExtraction`](../index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/PreFlightExtraction.kt#L42)

Check none the contract, relying entirely  on the HttpHandler code to raise a correct
LensFailure if extraction fails. Use this option to fully optimise performance, at the risk
of not checking

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(meta: `[`RouteMeta`](../../-route-meta/index.md)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensExtractor`](../../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../../../org.http4k.core/-request/index.md)`, *>>` |
