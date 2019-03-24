[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Composite](./index.md)

# Composite

`data class Composite : `[`ReadinessCheckResult`](../-readiness-check-result/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/ReadinessCheckResult.kt#L28)

Result of multiple checks, for which it reports an overall result (ie. any failure is fatal).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Composite(parts: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`> = emptyList())`<br>Result of multiple checks, for which it reports an overall result (ie. any failure is fatal). |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Properties

| Name | Summary |
|---|---|
| [pass](../-readiness-check-result/pass.md) | `val pass: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Functions

| Name | Summary |
|---|---|
| [iterator](iterator.md) | `fun iterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`): `[`Composite`](./index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
