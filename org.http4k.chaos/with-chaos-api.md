[http4k](../index.md) / [org.http4k.chaos](index.md) / [withChaosApi](./with-chaos-api.md)

# withChaosApi

`fun `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)`.withChaosApi(engine: `[`ChaosEngine`](-chaos-engine/index.md)` = ChaosEngine(), security: `[`Security`](../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`RoutingHttpHandler`](../org.http4k.routing/-routing-http-handler/index.md)

Mixin the set of remote Chaos API endpoints to a standard HttpHandler, using the passed ChaosStage.
Optionally a Security can be passed to limit access to the chaos controls.

