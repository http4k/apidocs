[http4k](../index.md) / [org.http4k.chaos](index.md) / [withChaosEngine](./with-chaos-engine.md)

# withChaosEngine

`fun `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`.withChaosEngine(stage: `[`Stage`](-stage.md)` = Wait, security: `[`Security`](../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L132)

Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage.
Optionally a Security can be passed to limit access to the chaos controls.

