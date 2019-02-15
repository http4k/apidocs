[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Secret](./index.md)

# Secret

`data class Secret` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/domain.kt#L34)

A secret is a value which tries very hard not to expose itself as a string

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Secret(bytes: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)`<br>A secret is a value which tries very hard not to expose itself as a string |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [stringValue](string-value.md) | `fun stringValue(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
