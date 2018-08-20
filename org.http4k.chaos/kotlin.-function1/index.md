[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [kotlin.Function1](./index.md)

### Extensions for kotlin.Function1

| Name | Summary |
|---|---|
| [and](and.md) | `infix fun `[`Trigger`](../-trigger.md)`.and(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
| [asFilter](as-filter.md) | `fun `[`Stage`](../-stage.md)`.asFilter(): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [inject](inject.md) | `fun `[`Policy`](../-policy.md)`.inject(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`Stage`](../-stage.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |
| [not](not.md) | `operator fun `[`Trigger`](../-trigger.md)`.not(): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](or.md) | `infix fun `[`Trigger`](../-trigger.md)`.or(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
| [then](then.md) | `fun `[`Stage`](../-stage.md)`.then(nextStage: `[`Stage`](../-stage.md)`): `[`Stage`](../-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `fun `[`Stage`](../-stage.md)`.until(trigger: `[`Trigger`](../-trigger.md)`): `[`Stage`](../-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [withChaosControls](with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosControls(stage: `[`Stage`](../-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", clock: Clock = systemUTC(), openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |
