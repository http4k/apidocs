[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensInjector](./index.md)

# LensInjector

`interface LensInjector<in IN, in OUT>`

### Functions

| Name | Summary |
|---|---|
| [inject](inject.md) | Lens operation to set the value into the target. Synomym for invoke(IN, OUT)`open fun <R : OUT> inject(value: IN, target: R): R` |
| [invoke](invoke.md) | Lens operation to set the value into the target`abstract operator fun <R : OUT> invoke(value: IN, target: R): R` |
| [of](of.md) | Bind this Lens to a value, so we can set it into a target`open infix fun <R : OUT> of(value: IN): (R) -> R` |
| [restrictInto](restrict-into.md) | Restrict the type that this Lens can inject into`open fun <NEXT : OUT> restrictInto(): `[`LensInjector`](./index.md)`<IN, NEXT>` |
| [set](set.md) | Lens operation to set the value into the target. Synomym for invoke(IN, OUT)`open operator fun <R : OUT> set(target: R, value: IN): R` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLens](../-bi-di-body-lens/index.md) | A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body.`class BiDiBodyLens<FINAL> : `[`LensInjector`](./index.md)`<FINAL, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](../-body-lens/index.md)`<FINAL>` |
| [BiDiLens](../-bi-di-lens/index.md) | A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target.`class BiDiLens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, FINAL> : `[`LensInjector`](./index.md)`<FINAL, IN>, `[`Lens`](../-lens/index.md)`<IN, FINAL>` |
| [BiDiPathLens](../-bi-di-path-lens/index.md) | `class BiDiPathLens<FINAL> : `[`LensInjector`](./index.md)`<FINAL, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`PathLens`](../-path-lens/index.md)`<FINAL>` |
| [LensInjectorExtractor](../-lens-injector-extractor.md) | `interface LensInjectorExtractor<IN, OUT> : `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>, `[`LensInjector`](./index.md)`<OUT, IN>` |
| [Store](../../org.http4k.core/-store/index.md) | `interface Store<OUT> : `[`LensInjector`](./index.md)`<OUT, `[`Request`](../../org.http4k.core/-request/index.md)`>, `[`LensExtractor`](../-lens-extractor/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, OUT>` |
