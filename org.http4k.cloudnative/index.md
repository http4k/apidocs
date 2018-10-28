[http4k](../index.md) / [org.http4k.cloudnative](./index.md)

## Package org.http4k.cloudnative

### Types

| Name | Summary |
|---|---|
| [Completed](-completed/index.md) | `data class Completed : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>The check completed successfully |
| [Composite](-composite/index.md) | `data class Composite : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>Result of multiple checks which calculates the overall result |
| [DefaultReadinessCheckResultRenderer](-default-readiness-check-result-renderer/index.md) | `object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](-readiness-check-result-renderer/index.md) |
| [Environment](-environment/index.md) | `data class Environment`<br>This models the runtime environment of the shell where the app is running |
| [EnvironmentKey](-environment-key/index.md) | `object EnvironmentKey : `[`BiDiLensSpec`](../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`Environment`](-environment/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [Failed](-failed/index.md) | `data class Failed : `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>The check failed |
| [Health](-health/index.md) | `object Health`<br>Represents the set of operational endpoints called by K8S to ensure that a particular pod is working ok. |
| [Http4kK8sServer](-http4k-k8s-server/index.md) | `class Http4kK8sServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)<br>A K8S server consists of a main application and a health application, running on 2 different ports. |
| [JsonReadinessCheckResultRenderer](-json-readiness-check-result-renderer/index.md) | `object JsonReadinessCheckResultRenderer` |
| [ReadinessCheck](-readiness-check/index.md) | `interface ReadinessCheck : () -> `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>A Readiness check is used to determine if the pod is ready to receive traffic. An example is to test if the app can talk to it's database. |
| [ReadinessCheckResult](-readiness-check-result/index.md) | `sealed class ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](-readiness-check-result/index.md)`>`<br>The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result. |
| [ReadinessCheckResultRenderer](-readiness-check-result-renderer/index.md) | `interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [plus](plus.md) | `operator fun `[`ReadinessCheckResult`](-readiness-check-result/index.md)`.plus(that: `[`ReadinessCheckResult`](-readiness-check-result/index.md)`): `[`Composite`](-composite/index.md) |
