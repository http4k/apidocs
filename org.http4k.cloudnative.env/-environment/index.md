[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Environment](./index.md)

# Environment

`data class Environment` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Environment.kt#L12)

This models the runtime environment of the shell where the app is running

### Functions

| Name | Summary |
|---|---|
| [overrides](overrides.md) | `infix fun overrides(that: `[`Environment`](./index.md)`): `[`Environment`](./index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [EMPTY](-e-m-p-t-y.md) | `val EMPTY: `[`Environment`](./index.md) |
| [ENV](-e-n-v.md) | `val ENV: `[`Environment`](./index.md)<br>Configuration from the runtime environment |
| [JVM_PROPERTIES](-j-v-m_-p-r-o-p-e-r-t-i-e-s.md) | `val JVM_PROPERTIES: `[`Environment`](./index.md)<br>Configuration from JVM properties (-D flags) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [defaults](defaults.md) | `fun defaults(vararg fn: (`[`Environment`](./index.md)`) -> `[`Environment`](./index.md)`): `[`Environment`](./index.md) |
| [from](from.md) | `fun from(file: `[`File`](http://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Environment`](./index.md)<br>`fun from(vararg pairs: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Environment`](./index.md) |
| [fromResource](from-resource.md) | `fun fromResource(resource: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Environment`](./index.md) |
