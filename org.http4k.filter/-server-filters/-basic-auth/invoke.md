[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [BasicAuth](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, authorize: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L91)

Credentials validation function

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L103)

Static username/password validation

`operator fun invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L108)

Static credentials validation

`operator fun <T> invoke(realm: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, key: `[`RequestContextLens`](../../../org.http4k.lens/-request-context-lens.md)`<`[`T`](invoke.md#T)`>, lookup: (`[`Credentials`](../../../org.http4k.core/-credentials/index.md)`) -> `[`T`](invoke.md#T)`?): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ServerFilters.kt#L113)

Population of a RequestContext with custom principal object

