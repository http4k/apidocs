[http4k](../index.md) / [org.http4k.lens](index.md) / [composite](./composite.md)

# composite

`inline fun <TARGET : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, reified T> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<TARGET, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.composite(crossinline fn: `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<TARGET, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.(TARGET) -> T): `[`Lens`](-lens/index.md)`<TARGET, T>`

This allows creation of a composite object from several values from the same source.

`inline fun <TARGET : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, reified T> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<TARGET, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.composite(crossinline getFn: `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<TARGET, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.(TARGET) -> T, crossinline setFn: T.(TARGET) -> TARGET): `[`BiDiLens`](-bi-di-lens/index.md)`<TARGET, T>`