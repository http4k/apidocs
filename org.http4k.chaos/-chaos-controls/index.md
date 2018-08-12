[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosControls](./index.md)

# ChaosControls

`object ChaosControls` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosControls.kt#L28)

Adds a set of endpoints to an application which will control the switching on/off of chaos behaviour. The added endpoints are:
//status &lt;- check the on off/status of the injected chaos
//activate &lt;- turn on the chaos
//deactivate &lt;- turn off the chaos
//toggle &lt;- toggle the chaos

By default, controls are mounted at the root path /chaos

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(trigger: `[`SwitchTrigger`](../-switch-trigger/index.md)`, chaosStage: `[`ChaosStage`](../-chaos-stage.md)`, controlsPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/chaos"): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
