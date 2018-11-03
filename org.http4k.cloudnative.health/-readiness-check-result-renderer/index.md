[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [ReadinessCheckResultRenderer](./index.md)

# ReadinessCheckResultRenderer

`interface ReadinessCheckResultRenderer : (`[`ReadinessCheckResult`](../-readiness-check-result/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/ReadinessCheckResultRenderer.kt#L10)

Renders the results of a readiness check

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `abstract val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [DefaultReadinessCheckResultRenderer](../-default-readiness-check-result-renderer/index.md) | `object DefaultReadinessCheckResultRenderer : `[`ReadinessCheckResultRenderer`](./index.md)<br>Basic reporting of ReadinessCheckResults |
