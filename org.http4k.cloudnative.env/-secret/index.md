[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Secret](./index.md)

# Secret

`class Secret : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array.
You can "use" the value only once, after which the value is destroyed

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Secret(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array. You can "use" the value only once, after which the value is destroyed`Secret(input: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [use](use.md) | `fun <T> use(fn: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> T): T` |
