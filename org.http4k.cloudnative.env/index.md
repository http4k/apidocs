[http4k](../index.md) / [org.http4k.cloudnative.env](./index.md)

## Package org.http4k.cloudnative.env

### Types

| Name | Summary |
|---|---|
| [Environment](-environment/index.md) | `class Environment`<br>This models the runtime environment of the shell where the app is running. Optionally pass a separator to use for multi-values otherwise a standard comma is used - this means you MUST override the separator if you have single values which contain commas, otherwise singular environment keys will just retrieve the first value. |
| [EnvironmentKey](-environment-key/index.md) | `object EnvironmentKey : `[`BiDiLensSpec`](../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`Environment`](-environment/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>This models the key used to get a value out of the  Environment using the standard Lens mechanic. Note that if your values contain commas, either use a EnvironmentKey.(mapping).multi.required()/optional()/defaulted() to retrieve the entire list, or override the comma separator in your initial Environment. |

### Functions

| Name | Summary |
|---|---|
| [main](main.md) | `fun main(args: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
