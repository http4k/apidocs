[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [ReadinessCheckResult](./index.md)

# ReadinessCheckResult

`sealed class ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](./index.md)`>`

The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result.

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pass](pass.md) | `val pass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`ReadinessCheckResult`](./index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`ReadinessCheckResult`](./index.md)`.plus(that: `[`ReadinessCheckResult`](./index.md)`): `[`Composite`](../-composite/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Completed](../-completed/index.md) | `data class Completed : `[`ReadinessCheckResult`](./index.md) |
| [Composite](../-composite/index.md) | Result of multiple checks, for which it reports an overall result (ie. any failure is fatal).`data class Composite : `[`ReadinessCheckResult`](./index.md) |
| [Failed](../-failed/index.md) | `data class Failed : `[`ReadinessCheckResult`](./index.md) |
