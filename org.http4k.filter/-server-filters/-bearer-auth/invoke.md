[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BearerAuth](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(token: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L148)

Static token validation

`operator fun invoke(checkToken: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L153)

Static token validation function

`operator fun <T> invoke(key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<`[`T`](invoke.md#T)`>, lookup: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`T`](invoke.md#T)`?): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L162)

Population of a RequestContext with custom principal object

