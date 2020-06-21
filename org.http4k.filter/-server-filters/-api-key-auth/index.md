[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [ApiKeyAuth](./index.md)

# ApiKeyAuth

`object ApiKeyAuth`

ApiKey token checking.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | ApiKey token checking using a typed lens.`operator fun <T> invoke(lens: `[`Lens`](../../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../../org.http4k.core/-request/index.md)`, T>, validate: (T) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md)<br>ApiKey token checking using standard request inspection.`operator fun invoke(validate: (`[`Request`](../../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
