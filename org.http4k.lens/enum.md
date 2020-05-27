[http4k](../index.md) / [org.http4k.lens](index.md) / [enum](./enum.md)

# enum

`fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, reified T : `[`Enum`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)`<T>> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<IN, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.enum(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<IN, T>`
`fun <reified T : `[`Enum`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)`<T>> `[`Path`](-path/index.md)`.enum(): `[`BiDiPathLensSpec`](-bi-di-path-lens-spec/index.md)`<T>`
`fun <reified T : `[`Enum`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)`<T>> `[`Query`](-query.md)`.enum(): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`Request`](../org.http4k.core/-request/index.md)`, T>`