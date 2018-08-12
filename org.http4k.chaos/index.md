[http4k](../index.md) / [org.http4k.chaos](./index.md)

## Package org.http4k.chaos

### Types

| Name | Summary |
|---|---|
| [ChaosBehaviour](-chaos-behaviour/index.md) | `interface ChaosBehaviour`<br>Encapsulates the type of bad behaviour to apply to the response. |
| [ChaosBehaviours](-chaos-behaviours/index.md) | `object ChaosBehaviours` |
| [ChaosControls](-chaos-controls/index.md) | `object ChaosControls`<br>Adds a set of endpoints to an application which will control the switching on/off of chaos behaviour. The added endpoints are: //status &lt;- check the on off/status of the injected chaos //activate &lt;- turn on the chaos //deactivate &lt;- turn off the chaos //toggle &lt;- toggle the chaos |
| [ChaosPolicies](-chaos-policies/index.md) | `object ChaosPolicies` |
| [ChaosPolicy](-chaos-policy/index.md) | `interface ChaosPolicy`<br>Determines whether or not to apply a particular type of ChaosBehaviour to a request/response. |
| [ChaosStage](-chaos-stage/index.md) | `interface ChaosStage`<br>Defines a periodic element during which a particular ChaosBehaviour is active. |
| [ChaosStages](-chaos-stages/index.md) | `object ChaosStages` |
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

### Functions

| Name | Summary |
|---|---|
| [asFilter](as-filter.md) | `fun `[`ChaosStage`](-chaos-stage/index.md)`.asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [then](then.md) | `fun `[`ChaosStage`](-chaos-stage/index.md)`.then(nextStage: `[`ChaosStage`](-chaos-stage/index.md)`): `[`ChaosStage`](-chaos-stage/index.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](until.md) | `fun `[`ChaosStage`](-chaos-stage/index.md)`.until(trigger: `[`ChaosTrigger`](-chaos-trigger.md)`): `[`ChaosStage`](-chaos-stage/index.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |
