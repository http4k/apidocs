[http4k](../../index.md) / [org.http4k.lens](../index.md) / [RequestContextKey](index.md) / [defaulted](./defaulted.md)

# defaulted

`fun <T> defaulted(store: `[`Store`](../../org.http4k.core/-store/index.md)`<`[`RequestContext`](../../org.http4k.core/-request-context/index.md)`>, default: T, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = UUID.randomUUID().toString()): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, T>`