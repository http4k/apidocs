[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Failed](./index.md)

# Failed

`data class Failed : `[`ReadinessCheckResult`](../-readiness-check-result/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/ReadinessCheckResult.kt#L30)

The check failed

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Failed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)``Failed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`)`<br>The check failed |

### Properties

| Name | Summary |
|---|---|
| [cause](cause.md) | `val cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pass](pass.md) | `val pass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [iterator](../-readiness-check-result/iterator.md) | `open fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`): `[`Composite`](../-composite/index.md) |
