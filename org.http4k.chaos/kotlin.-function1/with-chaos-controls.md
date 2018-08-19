[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [kotlin.Function1](index.md) / [withChaosControls](./with-chaos-controls.md)

# withChaosControls

`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`ChaosStage`](../-chaos-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", clock: Clock = systemUTC(), openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosControls.kt#L115)

Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage.
Optionally a Security can be passed to limit access to the chaos controls.

