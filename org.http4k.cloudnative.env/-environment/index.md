[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Environment](./index.md)

# Environment

`interface Environment` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Environment.kt#L15)

This models the runtime environment of the shell where the app is running. Optionally pass a separator to use for multi-values
otherwise a standard comma is used - this means you MUST override the separator if you have single values which contain commas, otherwise
singular environment keys will just retrieve the first value.

### Properties

| Name | Summary |
|---|---|
| [separator](separator.md) | `open val separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `abstract operator fun <T> get(key: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Environment`](./index.md)`, `[`T`](get.md#T)`>): `[`T`](get.md#T)<br>`abstract operator fun get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [overrides](overrides.md) | `open infix fun overrides(that: `[`Environment`](./index.md)`): `[`Environment`](./index.md)<br>Overlays the configuration set in this Environment on top of the values in the passed Environment. Used to chain: eg. Local File -&gt; System Properties -&gt; Env Properties -&gt; Defaults |
| [set](set.md) | `abstract operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [EMPTY](-e-m-p-t-y.md) | `val EMPTY: `[`Environment`](./index.md) |
| [ENV](-e-n-v.md) | `val ENV: `[`Environment`](./index.md)<br>Configuration from the runtime environment |
| [JVM_PROPERTIES](-j-v-m_-p-r-o-p-e-r-t-i-e-s.md) | `val JVM_PROPERTIES: `[`Environment`](./index.md)<br>Configuration from JVM properties (-D flags) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [defaults](defaults.md) | `fun defaults(vararg fn: (`[`Environment`](./index.md)`) -> `[`Environment`](./index.md)`): `[`Environment`](./index.md)<br>Setup default configuration mappings using EnvironmentKey lens bindings |
| [from](from.md) | `fun from(file: `[`File`](http://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Environment`](./index.md)<br>Load configuration from standard Properties file format on disk`fun from(vararg pairs: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Environment`](./index.md) |
| [fromResource](from-resource.md) | `fun fromResource(resource: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md)<br>Load configuration from standard Properties file format on classpath |
