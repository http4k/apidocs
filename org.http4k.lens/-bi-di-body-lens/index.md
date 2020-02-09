[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLens](./index.md)

# BiDiBodyLens

`class BiDiBodyLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<`[`FINAL`](index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](../-body-lens/index.md)`<`[`FINAL`](index.md#FINAL)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/body.kt#L31)

A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiBodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`FINAL`](index.md#FINAL)`, setLens: (`[`FINAL`](index.md#FINAL)`, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`)`<br>A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body. |

### Inherited Properties

| Name | Summary |
|---|---|
| [contentType](../-body-lens/content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [metas](../-body-lens/metas.md) | `val metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <R : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(value: `[`FINAL`](index.md#FINAL)`, target: `[`R`](invoke.md#R)`): `[`R`](invoke.md#R)<br>Lens operation to set the value into the target |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../-lens-injector/inject.md) | `open fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../-lens-injector/index.md#IN)`, target: `[`R`](../-lens-injector/inject.md#R)`): `[`R`](../-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../-body-lens/invoke.md) | `open operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`FINAL`](../-body-lens/index.md#FINAL)<br>Lens operation to get the value from the target |
| [of](../-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> of(value: `[`IN`](../-lens-injector/index.md#IN)`): (`[`R`](../-lens-injector/of.md#R)`) -> `[`R`](../-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../-lens-injector/index.md#OUT)`> set(target: `[`R`](../-lens-injector/set.md#R)`, value: `[`IN`](../-lens-injector/index.md#IN)`): `[`R`](../-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.chaos/kotlin.-function1/and.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.and(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [asFilter](../../org.http4k.chaos/kotlin.-function1/as-filter.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.asFilter(): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos stage to a standard http4k Filter. |
| [asK8sServer](../../org.http4k.cloudnative/kotlin.-function1/as-k8s-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, healthApp: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = Health(), healthPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8001): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md)<br>`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, env: `[`Environment`](../../org.http4k.cloudnative.env/-environment/index.md)` = ENV, healthApp: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = Health()): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md) |
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(fn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)<br>`fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.asServer(config: `[`WsServerConfig`](../../org.http4k.server/-ws-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)<br>`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [not](../../org.http4k.chaos/kotlin.-function1/not.md) | `operator fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.not(): (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](../../org.http4k.chaos/kotlin.-function1/or.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.or(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [testWsClient](../../org.http4k.testing/kotlin.-function1/test-ws-client.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.testWsClient(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
| [then](../../org.http4k.chaos/kotlin.-function1/then.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.then(nextStage: `[`Stage`](../../org.http4k.chaos/-stage.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../../org.http4k.chaos/kotlin.-function1/until.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.until(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosApi](../../org.http4k.chaos/kotlin.-function1/with-chaos-api.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.withChaosApi(engine: `[`ChaosEngine`](../../org.http4k.chaos/-chaos-engine/index.md)` = ChaosEngine(), security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Mixin the set of remote Chaos API endpoints to a standard HttpHandler, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |
| [withChaosControls](../../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.~~withChaosControls~~(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = ChaosStages.Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
