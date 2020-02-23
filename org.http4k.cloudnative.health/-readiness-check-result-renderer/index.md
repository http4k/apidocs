[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [ReadinessCheckResultRenderer](./index.md)

# ReadinessCheckResultRenderer

`interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)

Renders the results of a readiness check

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `abstract val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [DefaultReadinessCheckResultRenderer](../-default-readiness-check-result-renderer/index.md) | Basic reporting of ReadinessCheckResults`object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](./index.md) |
