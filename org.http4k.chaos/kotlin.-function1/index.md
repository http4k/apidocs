[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [kotlin.Function1](./index.md)

### Extensions for kotlin.Function1

| Name | Summary |
|---|---|
| [and](and.md) | `infix fun `[`Trigger`](../-trigger.md)`.and(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
| [asFilter](as-filter.md) | `fun `[`Stage`](../-stage.md)`.asFilter(): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos stage to a standard http4k Filter. |
| [not](not.md) | `operator fun `[`Trigger`](../-trigger.md)`.not(): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](or.md) | `infix fun `[`Trigger`](../-trigger.md)`.or(that: `[`Trigger`](../-trigger.md)`): `[`Trigger`](../-trigger.md) |
| [then](then.md) | `fun `[`Stage`](../-stage.md)`.then(nextStage: `[`Stage`](../-stage.md)`): `[`Stage`](../-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `fun `[`Stage`](../-stage.md)`.until(trigger: `[`Trigger`](../-trigger.md)`): `[`Stage`](../-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [withChaosApi](with-chaos-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosApi(engine: `[`ChaosEngine`](../-chaos-engine/index.md)` = ChaosEngine(), security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Mixin the set of remote Chaos API endpoints to a standard HttpHandler, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |
| [withChaosControls](with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.~~withChaosControls~~(stage: `[`Stage`](../-stage.md)` = ChaosStages.Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
