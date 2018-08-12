[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [kotlin.Function1](./index.md)

### Extensions for kotlin.Function1

| Name | Summary |
|---|---|
| [and](and.md) | `infix fun `[`ChaosTrigger`](../-chaos-trigger.md)`.and(that: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosTrigger`](../-chaos-trigger.md) |
| [asFilter](as-filter.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [inject](inject.md) | `fun `[`ChaosPolicy`](../-chaos-policy.md)`.inject(behaviour: `[`ChaosBehaviour`](../-chaos-behaviour.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |
| [not](not.md) | `operator fun `[`ChaosTrigger`](../-chaos-trigger.md)`.not(): (`[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](or.md) | `infix fun `[`ChaosTrigger`](../-chaos-trigger.md)`.or(that: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosTrigger`](../-chaos-trigger.md) |
| [then](then.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.then(nextStage: `[`ChaosStage`](../-chaos-stage.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.until(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [withChaosControls](with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`ChaosStage`](../-chaos-stage.md)`, preChaosFilter: `[`Filter`](../../org.http4k.core/-filter/index.md)` = Filter.NoOp, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", clock: Clock = systemUTC()): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Filter can be passed to limit access to the chaos controls. |
