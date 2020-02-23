[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Failed](./index.md)

# Failed

`data class Failed : `[`ReadinessCheckResult`](../-readiness-check-result/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Failed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`Failed(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [cause](cause.md) | `val cause: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](../-readiness-check-result/index.md)`): `[`Composite`](../-composite/index.md) |
