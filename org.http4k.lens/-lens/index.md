[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Lens](./index.md)

# Lens

`open class Lens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<IN, FINAL>, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Meta`](../-meta/index.md)`>`

A Lens provides the uni-directional extraction of an entity from a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A Lens provides the uni-directional extraction of an entity from a target.`Lens(meta: `[`Meta`](../-meta/index.md)`, lensGet: (IN) -> FINAL)` |

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `val meta: `[`Meta`](../-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to get the value from the target`open operator fun invoke(target: IN): FINAL` |
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`Meta`](../-meta/index.md)`>` |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiLens](../-bi-di-lens/index.md) | A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target.`class BiDiLens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, IN>, `[`Lens`](./index.md)`<IN, FINAL>` |
| [Mapping](../../org.http4k.jsonrpc/-mapping/index.md) | `class Mapping<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`Lens`](./index.md)`<IN, OUT>` |
| [PathLens](../-path-lens/index.md) | `open class PathLens<out FINAL> : `[`Lens`](./index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, FINAL>` |
