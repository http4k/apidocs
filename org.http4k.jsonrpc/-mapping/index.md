[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [Mapping](./index.md)

# Mapping

`class Mapping<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`Lens`](../../org.http4k.lens/-lens/index.md)`<IN, OUT>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Mapping(convert: (IN) -> OUT)` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../../org.http4k.lens/as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`>>` |
| [matches](../../org.http4k.lens/matches.md) | Check the content of any lens on a request for routing purposes.`fun <T> `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, T>.matches(fn: (T) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Router`](../../org.http4k.routing/-router/index.md) |
