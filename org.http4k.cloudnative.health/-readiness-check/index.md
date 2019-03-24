[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [ReadinessCheck](./index.md)

# ReadinessCheck

`interface ReadinessCheck : () -> `[`ReadinessCheckResult`](../-readiness-check-result/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/ReadinessCheckResult.kt#L7)

A Readiness check is used to determine if the pod is ready to receive traffic. An example is to test
if the app can talk to it's database.

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
