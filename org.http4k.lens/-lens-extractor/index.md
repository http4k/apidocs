[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](./index.md)

# LensExtractor

`interface LensExtractor<in IN, out OUT> : (IN) -> OUT`

### Functions

| Name | Summary |
|---|---|
| [extract](extract.md) | Lens operation to get the value from the target. Synonym for invoke(IN)`open fun extract(target: IN): OUT` |
| [get](get.md) | Lens operation to get the value from the target. Synonym for invoke(IN)`open operator fun <R : IN> get(target: R): OUT` |
| [invoke](invoke.md) | Lens operation to get the value from the target`abstract operator fun invoke(target: IN): OUT` |
| [restrictFrom](restrict-from.md) | Restrict the type that this Lens can extract from`open fun <NEXT : IN> restrictFrom(): `[`LensExtractor`](./index.md)`<NEXT, OUT>` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](./index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](./index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |

### Inheritors

| Name | Summary |
|---|---|
| [BodyLens](../-body-lens/index.md) | A BodyLens provides the uni-directional extraction of an entity from a target body.`open class BodyLens<out FINAL> : `[`LensExtractor`](./index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, FINAL>` |
| [Lens](../-lens/index.md) | A Lens provides the uni-directional extraction of an entity from a target.`open class Lens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, out FINAL> : `[`LensExtractor`](./index.md)`<IN, FINAL>, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Meta`](../-meta/index.md)`>` |
| [LensInjectorExtractor](../-lens-injector-extractor.md) | `interface LensInjectorExtractor<IN, OUT> : `[`LensExtractor`](./index.md)`<IN, OUT>, `[`LensInjector`](../-lens-injector/index.md)`<OUT, IN>` |
| [Store](../../org.http4k.core/-store/index.md) | `interface Store<OUT> : `[`LensInjector`](../-lens-injector/index.md)`<OUT, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`LensExtractor`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, OUT>` |
| [WsMessageLens](../-ws-message-lens/index.md) | A WsMessageLens provides the extraction of an entity from a target WsMessage.`open class WsMessageLens<out FINAL> : `[`LensExtractor`](./index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, FINAL>` |
