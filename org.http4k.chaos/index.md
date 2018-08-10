[http4k](../index.md) / [org.http4k.chaos](./index.md)

## Package org.http4k.chaos

### Types

| Name | Summary |
|---|---|
| [ChaosBehaviour](-chaos-behaviour/index.md) | `interface ChaosBehaviour`<br>Encapsulates the type of bad behaviour to apply to the response. |
| [ChaosControls](-chaos-controls/index.md) | `object ChaosControls`<br>Adds a set of endpoints to an application which will control the switching on/off of chaos behaviour. The added endpoints are: //status &lt;- check the on off/status of the injected chaos //activate &lt;- turn on the chaos //deactivate &lt;- turn off the chaos //toggle &lt;- toggle the chaos |
| [ChaosPolicy](-chaos-policy/index.md) | `interface ChaosPolicy`<br>Determines whether or not to apply a particular type of ChaosBehaviour to a request/response. |
| [ChaosStage](-chaos-stage/index.md) | `interface ChaosStage`<br>Defines a periodic element during which a particular ChaosBehaviour is active. |
| [ChaosTriggers](-chaos-triggers/index.md) | `object ChaosTriggers` |
| [SerializableTrigger](-serializable-trigger/index.md) | `abstract class SerializableTrigger` |
| [SwitchTrigger](-switch-trigger/index.md) | `class SwitchTrigger : `[`ChaosTrigger`](-chaos-trigger.md)<br>Simple toggleable trigger to turn ChaosBehaviour on/off |

### Type Aliases

| Name | Summary |
|---|---|
| [ChaosTrigger](-chaos-trigger.md) | `typealias ChaosTrigger = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [CHAOS](-c-h-a-o-s.md) | `val `[`Common`](../org.http4k.lens/-header/-common/index.md)`.CHAOS: `[`BiDiLens`](../org.http4k.lens/-bi-di-lens/index.md)`<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
