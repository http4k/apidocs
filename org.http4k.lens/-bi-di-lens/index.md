[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiLens](./index.md)

# BiDiLens

`class BiDiLens<in IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, IN>, `[`Lens`](../-lens/index.md)`<IN, FINAL>`

A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity
into a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A BiDiLens provides the bi-directional extraction of an entity from a target, or the insertion of an entity into a target.`BiDiLens(meta: `[`Meta`](../-meta/index.md)`, get: (IN) -> FINAL, lensSet: (FINAL, IN) -> IN)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to set the value into the target`operator fun <R : IN> invoke(value: FINAL, target: R): R` |
