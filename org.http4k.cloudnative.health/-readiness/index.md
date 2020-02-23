[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Readiness](./index.md)

# Readiness

`object Readiness`

The Readiness check is used to determine if an app is prepared to receive live traffic.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(checks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ReadinessCheck`](../-readiness-check/index.md)`> = emptyList(), renderer: `[`ReadinessCheckResultRenderer`](../-readiness-check-result-renderer/index.md)` = DefaultReadinessCheckResultRenderer): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
