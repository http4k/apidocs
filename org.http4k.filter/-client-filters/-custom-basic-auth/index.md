[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [CustomBasicAuth](./index.md)

# CustomBasicAuth

`object CustomBasicAuth`

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(header: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, provider: () -> `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter.md)<br>`operator fun invoke(header: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, user: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, password: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../../org.http4k.core/-filter.md)<br>`operator fun invoke(header: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, credentials: `[`Credentials`](../../../org.http4k.core/-credentials/index.md)`): `[`Filter`](../../../org.http4k.core/-filter.md) |
