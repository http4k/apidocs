[http4k](../index.md) / [org.http4k.cloudnative.health](./index.md)

## Package org.http4k.cloudnative.health

### Types

| Name | Summary |
|---|---|
| [Completed](-completed/index.md) | `data class Completed : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>The check completed successfully |
| [Composite](-composite/index.md) | `data class Composite : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>Result of multiple checks which calculates the overall result |
| [DefaultReadinessCheckResultRenderer](-default-readiness-check-result-renderer/index.md) | `object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](-readiness-check-result-renderer/index.md) |
| [Failed](-failed/index.md) | `data class Failed : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>The check failed |
| [Health](-health/index.md) | `object Health`<br>Represents the set of operational endpoints to ensure that a particular pod is working ok. |
| [JsonReadinessCheckResultRenderer](-json-readiness-check-result-renderer/index.md) | `object JsonReadinessCheckResultRenderer` |
| [Liveness](-liveness.md) | `object Liveness : `[`HttpHandler`](../org.http4k.core/-http-handler.md)<br>The Liveness check is used to determine if an app is alive. |
| [Readiness](-readiness/index.md) | `object Readiness`<br>The Readiness check is used to determine if an app is prepared to receive live traffic. |
| [ReadinessCheck](-readiness-check/index.md) | `interface ReadinessCheck : () -> `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>A Readiness check is used to determine if the pod is ready to receive traffic. An example is to test if the app can talk to it's database. |
| [ReadinessCheckResult](-readiness-check-result/index.md) | `sealed class ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](-readiness-check-result/index.md)`>`<br>The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result. |
| [ReadinessCheckResultRenderer](-readiness-check-result-renderer/index.md) | `interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Renders the results of a readiness check into |

### Functions

| Name | Summary |
|---|---|
| [plus](plus.md) | `operator fun `[`ReadinessCheckResult`](-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](-readiness-check-result/index.md)`): `[`Composite`](-composite/index.md) |
