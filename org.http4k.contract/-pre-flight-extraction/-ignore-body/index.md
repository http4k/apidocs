[http4k](../../../index.md) / [org.http4k.contract](../../index.md) / [PreFlightExtraction](../index.md) / [IgnoreBody](./index.md)

# IgnoreBody

`object IgnoreBody : `[`PreFlightExtraction`](../index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/PreFlightExtraction.kt#L32)

Check all parts of the contract apart from the body, relying on the HttpHandler code to raise a correct
LensFailure if extraction fails. Use this option to avoid re-extracting the body multiple times.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(meta: `[`RouteMeta`](../../-route-meta/index.md)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Lens`](../../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../../org.http4k.core/-request/index.md)`, *>>` |
