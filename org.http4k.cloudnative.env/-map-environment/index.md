[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [MapEnvironment](./index.md)

# MapEnvironment

`class MapEnvironment : `[`Environment`](../-environment/index.md)

### Properties

| Name | Summary |
|---|---|
| [separator](separator.md) | `val separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `operator fun <T> get(key: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Environment`](../-environment/index.md)`, T>): T`<br>`operator fun get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [keys](keys.md) | `fun keys(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [minus](minus.md) | `fun minus(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](../-environment/index.md) |
| [set](set.md) | `operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MapEnvironment`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(properties: `[`Properties`](https://docs.oracle.com/javase/9/docs/api/java/util/Properties.html)`, separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ","): `[`Environment`](../-environment/index.md)<br>`fun from(reader: `[`Reader`](https://docs.oracle.com/javase/9/docs/api/java/io/Reader.html)`, separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ","): `[`Environment`](../-environment/index.md) |
