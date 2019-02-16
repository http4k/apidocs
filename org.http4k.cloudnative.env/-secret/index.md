[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Secret](./index.md)

# Secret

`data class Secret : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Secret.kt#L9)

A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array. It is also able to be cleared after construction.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Secret(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)``Secret(value: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)`<br>A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array. It is also able to be cleared after construction. |

### Properties

| Name | Summary |
|---|---|
| [value](value.md) | `val value: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |

### Functions

| Name | Summary |
|---|---|
| [clear](clear.md) | `fun clear(): `[`Secret`](./index.md) |
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [stringValue](string-value.md) | `fun stringValue(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
