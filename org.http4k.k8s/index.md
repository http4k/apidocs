[http4k](../index.md) / [org.http4k.k8s](./index.md)

## Package org.http4k.k8s

### Types

| Name | Summary |
|---|---|
| [DefaultReadinessCheckResultRenderer](-default-readiness-check-result-renderer/index.md) | `object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](-readiness-check-result-renderer/index.md) |
| [Health](-health/index.md) | `object Health`<br>Represents the set of operational endpoints called by K8S to ensure that a particular pod is working ok. |
| [Http4kK8sServer](-http4k-k8s-server/index.md) | `class Http4kK8sServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)<br>A K8S server consists of a main application and a health application, running on 2 different ports. |
| [JsonReadinessCheckResultRenderer](-json-readiness-check-result-renderer/index.md) | `object JsonReadinessCheckResultRenderer` |
| [ReadinessCheckResult](-readiness-check-result/index.md) | `interface ReadinessCheckResult : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`ReadinessCheckResult`](-readiness-check-result/index.md)`>`<br>The result of a Readiness check. Checks can be combined together with `+()` to provide an overall result. |
| [ReadinessCheckResultRenderer](-readiness-check-result-renderer/index.md) | `interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Type Aliases

| Name | Summary |
|---|---|
| [ReadinessCheck](-readiness-check.md) | `typealias ReadinessCheck = () -> `[`ReadinessCheckResult`](-readiness-check-result/index.md)<br>A Readiness check is used by K8S to determine if the pod is ready to receive traffic. An example is to test if the app can talk to it's database. |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |
