[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [RemoteChaosApi](./index.md)

# RemoteChaosApi

`object RemoteChaosApi`

A set of endpoints to an application which will control the setting and toggling chaos behaviour. The added endpoints are:
GET //status &lt;- check the on off/status of the injected chaos
POST //activate &lt;- turn on the chaos. optionally POST a JSON body to set a list of new stages to use.
POST //deactivate &lt;- turn off the chaos
POST //toggle &lt;- toggle the chaos

By default, controls are mounted at the root path /chaos

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(engine: `[`ChaosEngine`](../-chaos-engine/index.md)`, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", chaosSecurity: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
