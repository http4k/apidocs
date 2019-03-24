[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Readiness](./index.md)

# Readiness

`object Readiness` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/Health.kt#L39)

The Readiness check is used to determine if an app is prepared to receive live traffic.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(checks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ReadinessCheck`](../-readiness-check/index.md)`> = emptyList(), renderer: `[`ReadinessCheckResultRenderer`](../-readiness-check-result-renderer/index.md)` = DefaultReadinessCheckResultRenderer): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
