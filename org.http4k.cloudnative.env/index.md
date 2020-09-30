[http4k](../index.md) / [org.http4k.cloudnative.env](./index.md)

## Package org.http4k.cloudnative.env

### Types

| Name | Summary |
|---|---|
| [Authority](-authority/index.md) | `data class Authority` |
| [Environment](-environment/index.md) | This models the runtime environment of the shell where the app is running. Optionally pass a separator to use for multi-values otherwise a standard comma is used - this means you MUST override the separator if you have single values which contain commas, otherwise singular environment keys will just retrieve the first value.`interface Environment` |
| [EnvironmentKey](-environment-key/index.md) | This models the key used to get a value out of the Environment using the standard Lens mechanic. Note that if your values contain commas, either use a EnvironmentKey.(mapping).multi.required()/optional()/defaulted() to retrieve the entire list, or override the comma separator in your initial Environment.`object EnvironmentKey : `[`BiDiLensSpec`](../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`Environment`](-environment/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [Host](-host/index.md) | `data class Host` |
| [MapEnvironment](-map-environment/index.md) | `class MapEnvironment : `[`Environment`](-environment/index.md) |
| [Port](-port/index.md) | `data class Port` |
| [Secret](-secret/index.md) | A secret is a value which tries very hard not to expose itself as a string, by storing it's value in a byte array. You can "use" the value only once, after which the value is destroyed`class Secret : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html) |
| [Timeout](-timeout/index.md) | `data class Timeout` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [fromConfigFile](from-config-file.md) | `fun Environment.Companion.fromConfigFile(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`Environment`](-environment/index.md) |
| [fromYaml](from-yaml.md) | Read a YAML file into environments, prepending all of the nested levels into the property names`fun Environment.Companion.fromYaml(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`Environment`](-environment/index.md) |
