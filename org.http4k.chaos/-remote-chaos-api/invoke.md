[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [RemoteChaosApi](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(engine: `[`ChaosEngine`](../-chaos-engine/index.md)`, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", chaosSecurity: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)