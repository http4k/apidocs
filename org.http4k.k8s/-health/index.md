[http4k](../../index.md) / [org.http4k.k8s](../index.md) / [Health](./index.md)

# Health

`object Health` [(source)](https://github.com/http4k/http4k/blob/master/http4k-k8s/src/main/kotlin/org/http4k/k8s/Health.kt#L16)

Represents the set of operational endpoints called by K8S to ensure that a particular pod is working ok.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(renderer: `[`ReadinessCheckResultRenderer`](../-readiness-check-result-renderer/index.md)` = DefaultReadinessCheckResultRenderer, vararg checks: `[`ReadinessCheck`](../-readiness-check.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
