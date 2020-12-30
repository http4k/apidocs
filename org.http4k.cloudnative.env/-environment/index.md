[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Environment](./index.md)

# Environment

`interface Environment`

This models the runtime environment of the shell where the app is running. Optionally pass a separator to use for
multi-values otherwise a standard comma is used - this means you MUST override the separator if you have single values
which contain commas, otherwise singular environment keys will just retrieve the first value.

### Properties

| Name | Summary |
|---|---|
| [separator](separator.md) | `open val separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `abstract operator fun <T> get(key: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Environment`](./index.md)`, T>): T`<br>`abstract operator fun get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [keys](keys.md) | `abstract fun keys(): `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [minus](minus.md) | `abstract operator fun minus(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md) |
| [overrides](overrides.md) | Overlays the configuration set in this Environment on top of the values in the passed Environment. Used to chain: eg. Local File -&gt; System Properties -&gt; Env Properties -&gt; Defaults`open infix fun overrides(that: `[`Environment`](./index.md)`): `[`Environment`](./index.md) |
| [set](set.md) | `abstract operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [EMPTY](-e-m-p-t-y.md) | `val EMPTY: `[`Environment`](./index.md) |
| [ENV](-e-n-v.md) | Configuration from the runtime environment`val ENV: `[`Environment`](./index.md) |
| [JVM_PROPERTIES](-j-v-m_-p-r-o-p-e-r-t-i-e-s.md) | Configuration from JVM properties (-D flags)`val JVM_PROPERTIES: `[`Environment`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [defaults](defaults.md) | Setup default configuration mappings using EnvironmentKey lens bindings`fun defaults(vararg fn: (`[`Environment`](./index.md)`) -> `[`Environment`](./index.md)`): `[`Environment`](./index.md) |
| [from](from.md) | Load configuration from standard Properties file format on disk`fun from(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`Environment`](./index.md)`fun from(vararg pairs: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Environment`](./index.md)<br>`fun from(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Environment`](./index.md) |
| [fromResource](from-resource.md) | Load configuration from standard Properties file format on classpath`fun fromResource(resource: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun `[`Environment`](./index.md)`.with(vararg modifiers: (`[`Environment`](./index.md)`) -> `[`Environment`](./index.md)`): `[`Environment`](./index.md) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [fromConfigFile](../from-config-file.md) | `fun Environment.Companion.fromConfigFile(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`Environment`](./index.md) |
| [fromYaml](../from-yaml.md) | Read a YAML file into environments, prepending all of the nested levels into the property names`fun Environment.Companion.fromYaml(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`Environment`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [MapEnvironment](../-map-environment/index.md) | `class MapEnvironment : `[`Environment`](./index.md) |
