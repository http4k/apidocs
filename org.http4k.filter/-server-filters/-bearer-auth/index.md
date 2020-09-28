[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BearerAuth](./index.md)

# BearerAuth

`object BearerAuth`

Bearer Auth token checking.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Static token validation`operator fun invoke(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): <ERROR CLASS>`<br>Static token validation function`operator fun invoke(checkToken: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): <ERROR CLASS>`<br>Population of a RequestContext with custom principal object`operator fun <T> invoke(key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<T>, lookup: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> T?): <ERROR CLASS>` |
