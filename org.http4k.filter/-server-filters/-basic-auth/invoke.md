[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BasicAuth](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authorize: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): <ERROR CLASS>`

Credentials validation function

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): <ERROR CLASS>`

Static username/password validation

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): <ERROR CLASS>`

Static credentials validation

`operator fun <T> invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<T>, lookup: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> T?): <ERROR CLASS>`

Population of a RequestContext with custom principal object

