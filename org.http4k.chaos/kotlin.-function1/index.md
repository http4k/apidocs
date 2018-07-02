[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [kotlin.Function1](./index.md)

### Extensions for kotlin.Function1

| Name | Summary |
|---|---|
| [not](not.md) | `operator fun `[`ChaosTrigger`](../-chaos-trigger.md)`.not(): (`[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [withChaosControls](with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`ChaosStage`](../-chaos-stage/index.md)`, preChaosFilter: `[`Filter`](../../org.http4k.core/-filter/index.md)` = Filter.NoOp, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", clock: Clock = systemUTC()): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Filter can be passed to limit access to the chaos controls. |
