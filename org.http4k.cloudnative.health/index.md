[http4k](../index.md) / [org.http4k.cloudnative.health](./index.md)

## Package org.http4k.cloudnative.health

### Types

| Name | Summary |
|---|---|
| [Completed](-completed/index.md) | `data class Completed : `[`ReadinessCheckResult`](-readiness-check-result/index.md) |
| [Composite](-composite/index.md) | Result of multiple checks, for which it reports an overall result (ie. any failure is fatal).`data class Composite : `[`ReadinessCheckResult`](-readiness-check-result/index.md) |
| [DefaultReadinessCheckResultRenderer](-default-readiness-check-result-renderer/index.md) | Basic reporting of ReadinessCheckResults`object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](-readiness-check-result-renderer/index.md) |
| [Failed](-failed/index.md) | `data class Failed : `[`ReadinessCheckResult`](-readiness-check-result/index.md) |
| [Health](-health/index.md) | Represents the set of operational endpoints to ensure that a particular app is working ok. By default provides Readiness and Liveness endpoints, but extra routes can be passed, as can a different renderer implementation for the ReadinessCheck results.`object Health` |
| [JsonReadinessCheckResultRenderer](-json-readiness-check-result-renderer/index.md) | Reporting of ReadinessCheckResults in a JSON tree`object JsonReadinessCheckResultRenderer` |
| [Liveness](-liveness.md) | The Liveness check is used to determine if an app is alive.`object Liveness : `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [Readiness](-readiness/index.md) | The Readiness check is used to determine if an app is prepared to receive live traffic.`object Readiness` |
| [ReadinessCheck](-readiness-check/index.md) | A Readiness check is used to determine if the pod is ready to receive traffic. An example is to test if the app can talk to it's database.`interface ReadinessCheck : () -> `[`ReadinessCheckResult`](-readiness-check-result/index.md) |
| [ReadinessCheckResult](-readiness-check-result/index.md) | The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result.`sealed class ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](-readiness-check-result/index.md)`>` |
| [ReadinessCheckResultRenderer](-readiness-check-result-renderer/index.md) | Renders the results of a readiness check`interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [plus](plus.md) | `operator fun `[`ReadinessCheckResult`](-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](-readiness-check-result/index.md)`): `[`Composite`](-composite/index.md) |
