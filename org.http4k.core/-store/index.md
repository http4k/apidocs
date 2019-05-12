[http4k](../../index.md) / [org.http4k.core](../index.md) / [Store](./index.md)

# Store

`interface Store<OUT> : `[`LensInjector`](../../org.http4k.lens/-lens-injector/index.md)`<`[`OUT`](index.md#OUT)`, `[`Request`](../-request/index.md)`>, `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../-request/index.md)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Store.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [remove](remove.md) | `abstract fun remove(value: `[`OUT`](index.md#OUT)`): `[`OUT`](index.md#OUT)`?` |

### Inherited Functions

| Name | Summary |
|---|---|
| [extract](../../org.http4k.lens/-lens-extractor/extract.md) | `open fun extract(target: `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [get](../../org.http4k.lens/-lens-extractor/get.md) | `open operator fun <R : `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`> get(target: `[`R`](../../org.http4k.lens/-lens-extractor/get.md#R)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target. Synonym for invoke(IN) |
| [inject](../../org.http4k.lens/-lens-injector/inject.md) | `open fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> inject(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`, target: `[`R`](../../org.http4k.lens/-lens-injector/inject.md#R)`): `[`R`](../../org.http4k.lens/-lens-injector/inject.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |
| [invoke](../../org.http4k.lens/-lens-injector/invoke.md) | `abstract operator fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> invoke(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`, target: `[`R`](../../org.http4k.lens/-lens-injector/invoke.md#R)`): `[`R`](../../org.http4k.lens/-lens-injector/invoke.md#R)<br>Lens operation to set the value into the target |
| [invoke](../../org.http4k.lens/-lens-extractor/invoke.md) | `abstract operator fun invoke(target: `[`IN`](../../org.http4k.lens/-lens-extractor/index.md#IN)`): `[`OUT`](../../org.http4k.lens/-lens-extractor/index.md#OUT)<br>Lens operation to get the value from the target |
| [of](../../org.http4k.lens/-lens-injector/of.md) | `open infix fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> of(value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`): (`[`R`](../../org.http4k.lens/-lens-injector/of.md#R)`) -> `[`R`](../../org.http4k.lens/-lens-injector/of.md#R)<br>Bind this Lens to a value, so we can set it into a target |
| [set](../../org.http4k.lens/-lens-injector/set.md) | `open operator fun <R : `[`OUT`](../../org.http4k.lens/-lens-injector/index.md#OUT)`> set(target: `[`R`](../../org.http4k.lens/-lens-injector/set.md#R)`, value: `[`IN`](../../org.http4k.lens/-lens-injector/index.md#IN)`): `[`R`](../../org.http4k.lens/-lens-injector/set.md#R)<br>Lens operation to set the value into the target. Synomym for invoke(IN, OUT) |

### Extension Functions

| Name | Summary |
|---|---|
| [and](../../org.http4k.chaos/kotlin.-function1/and.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.and(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [asFilter](../../org.http4k.chaos/kotlin.-function1/as-filter.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.asFilter(): `[`Filter`](../-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [asK8sServer](../../org.http4k.cloudnative/kotlin.-function1/as-k8s-server.md) | `fun `[`HttpHandler`](../-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, healthApp: `[`HttpHandler`](../-http-handler.md)` = Health(), healthPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8001): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md)<br>`fun `[`HttpHandler`](../-http-handler.md)`.asK8sServer(serverConfig: (port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, env: `[`Environment`](../../org.http4k.cloudnative.env/-environment/index.md)` = ENV, healthApp: `[`HttpHandler`](../-http-handler.md)` = Health()): `[`Http4kK8sServer`](../../org.http4k.cloudnative/-http4k-k8s-server/index.md) |
| [asServer](../../org.http4k.server/kotlin.-function1/as-server.md) | `fun `[`HttpHandler`](../-http-handler.md)`.asServer(fn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`, port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)<br>`fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.asServer(config: `[`WsServerConfig`](../../org.http4k.server/-ws-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)<br>`fun `[`HttpHandler`](../-http-handler.md)`.asServer(config: `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)`): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [asServlet](../../org.http4k.servlet/kotlin.-function1/as-servlet.md) | `fun `[`HttpHandler`](../-http-handler.md)`.asServlet(): `[`HttpHandlerServlet`](../../org.http4k.servlet/-http-handler-servlet/index.md) |
| [not](../../org.http4k.chaos/kotlin.-function1/not.md) | `operator fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.not(): (`[`Request`](../-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [or](../../org.http4k.chaos/kotlin.-function1/or.md) | `infix fun `[`Trigger`](../../org.http4k.chaos/-trigger.md)`.or(that: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Trigger`](../../org.http4k.chaos/-trigger.md) |
| [testWsClient](../../org.http4k.testing/kotlin.-function1/test-ws-client.md) | `fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.testWsClient(request: `[`Request`](../-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
| [then](../../org.http4k.chaos/kotlin.-function1/then.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.then(nextStage: `[`Stage`](../../org.http4k.chaos/-stage.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../../org.http4k.chaos/kotlin.-function1/until.md) | `fun `[`Stage`](../../org.http4k.chaos/-stage.md)`.until(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |
| [withAsyncApi](../../org.http4k.client/kotlin.-function1/with-async-api.md) | `fun `[`HttpHandler`](../-http-handler.md)`.withAsyncApi(): `[`AsyncHttpClient`](../../org.http4k.client/-async-http-client/index.md)<br>Convert a synchronous HttpHandler API to mimic AsyncHttpClient |
| [withChaosControls](../../org.http4k.chaos/kotlin.-function1/with-chaos-controls.md) | `fun `[`HttpHandler`](../-http-handler.md)`.~~withChaosControls~~(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = ChaosStages.Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = CorsPolicy.UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [withChaosEngine](../../org.http4k.chaos/kotlin.-function1/with-chaos-engine.md) | `fun `[`HttpHandler`](../-http-handler.md)`.withChaosEngine(stage: `[`Stage`](../../org.http4k.chaos/-stage.md)` = Wait, security: `[`Security`](../../org.http4k.contract.security/-security/index.md)` = NoSecurity, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos", openApiPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", corsPolicy: `[`CorsPolicy`](../../org.http4k.filter/-cors-policy/index.md)` = UnsafeGlobalPermissive): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)<br>Convert a standard HttpHandler to be Chaos-enabled, using the passed ChaosStage. Optionally a Security can be passed to limit access to the chaos controls. |

### Inheritors

| Name | Summary |
|---|---|
| [RequestContexts](../-request-contexts/index.md) | `class RequestContexts : `[`Store`](./index.md)`<`[`RequestContext`](../-request-context/index.md)`>`<br>In-memory RequestContext store. |
