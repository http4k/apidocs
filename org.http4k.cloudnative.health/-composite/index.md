[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Composite](./index.md)

# Composite

`data class Composite : `[`ReadinessCheckResult`](../-readiness-check-result/index.md)

Result of multiple checks, for which it reports an overall result (ie. any failure is fatal).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Result of multiple checks, for which it reports an overall result (ie. any failure is fatal).`Composite(parts: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`> = emptyList())` |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [iterator](iterator.md) | `fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`): `[`Composite`](./index.md) |
