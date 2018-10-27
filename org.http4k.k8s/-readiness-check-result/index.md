[http4k](../../index.md) / [org.http4k.k8s](../index.md) / [ReadinessCheckResult](./index.md)

# ReadinessCheckResult

`interface ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](./index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-k8s/src/main/kotlin/org/http4k/k8s/ReadinessCheckResult.kt#L12)

The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result.

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pass](pass.md) | `abstract val pass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [iterator](iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`ReadinessCheckResult`](./index.md)`>` |
| [plus](plus.md) | `open operator fun plus(that: `[`ReadinessCheckResult`](./index.md)`): `[`ReadinessCheckResult`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(pass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "success"): `[`ReadinessCheckResult`](./index.md)<br>a Default implementation of a result. |
