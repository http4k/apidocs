[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BearerAuth](./index.md)

# BearerAuth

`object BearerAuth` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L146)

Bearer Auth token checking.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Static token validation`operator fun invoke(checkToken: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Static token validation function`operator fun <T> invoke(key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<`[`T`](invoke.md#T)`>, lookup: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`T`](invoke.md#T)`?): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>Population of a RequestContext with custom principal object |
