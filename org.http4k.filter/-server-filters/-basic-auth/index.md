[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BasicAuth](./index.md)

# BasicAuth

`object BasicAuth`

Simple Basic Auth credential checking.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Credentials validation function`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authorize: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Static username/password validation`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Static credentials validation`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Population of a RequestContext with custom principal object`operator fun <T> invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<T>, lookup: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> T?): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
