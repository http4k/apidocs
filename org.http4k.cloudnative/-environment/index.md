[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [Environment](./index.md)

# Environment

`data class Environment` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/Environment.kt#L9)

This models the runtime environment of the shell where the app is running

### Functions

| Name | Summary |
|---|---|
| [overrides](overrides.md) | `infix fun overrides(that: `[`Environment`](./index.md)`): `[`Environment`](./index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [EMPTY](-e-m-p-t-y.md) | `val EMPTY: `[`Environment`](./index.md) |
| [ENV](-e-n-v.md) | `val ENV: `[`Environment`](./index.md)<br>Use this inside K8s |
| [JVM_PROPERTIES](-j-v-m_-p-r-o-p-e-r-t-i-e-s.md) | `val JVM_PROPERTIES: `[`Environment`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(vararg pairs: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Environment`](./index.md) |
