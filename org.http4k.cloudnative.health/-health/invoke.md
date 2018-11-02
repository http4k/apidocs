[http4k](../../index.md) / [org.http4k.cloudnative.health](../index.md) / [Health](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(vararg extraRoutes: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`, checks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ReadinessCheck`](../-readiness-check/index.md)`> = emptyList(), renderer: `[`ReadinessCheckResultRenderer`](../-readiness-check-result-renderer/index.md)` = DefaultReadinessCheckResultRenderer): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/health/Health.kt#L18)