[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [MapEnvironment](./index.md)

# MapEnvironment

`class MapEnvironment : `[`Environment`](../-environment/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Environment.kt#L74)

### Properties

| Name | Summary |
|---|---|
| [separator](separator.md) | `val separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `operator fun <T> get(key: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Environment`](../-environment/index.md)`, `[`T`](get.md#T)`>): `[`T`](get.md#T)<br>`operator fun get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [keys](keys.md) | `fun keys(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [minus](minus.md) | `fun minus(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](../-environment/index.md) |
| [set](set.md) | `operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MapEnvironment`](./index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [overrides](../-environment/overrides.md) | `open infix fun overrides(that: `[`Environment`](../-environment/index.md)`): `[`Environment`](../-environment/index.md)<br>Overlays the configuration set in this Environment on top of the values in the passed Environment. Used to chain: eg. Local File -&gt; System Properties -&gt; Env Properties -&gt; Defaults |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(properties: `[`Properties`](https://docs.oracle.com/javase/9/docs/api/java/util/Properties.html)`, separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ","): `[`Environment`](../-environment/index.md)<br>`fun from(reader: `[`Reader`](https://docs.oracle.com/javase/9/docs/api/java/io/Reader.html)`, separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ","): `[`Environment`](../-environment/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
