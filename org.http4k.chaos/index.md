[http4k](../index.md) / [org.http4k.chaos](./index.md)

## Package org.http4k.chaos

### Types

| Name | Summary |
|---|---|
| [ChaosBehaviours](-chaos-behaviours/index.md) | `object ChaosBehaviours` |
| [ChaosControls](-chaos-controls/index.md) | `object ChaosControls`<br>Adds a set of endpoints to an application which will control the switching on/off of chaos behaviour. The added endpoints are: GET //status &lt;- check the on off/status of the injected chaos POST //activate &lt;- turn on the chaos. optionally POST a JSON body to set a list of new stages to use. POST //deactivate &lt;- turn off the chaos POST //toggle &lt;- toggle the chaos |
| [ChaosStages](-chaos-stages/index.md) | `object ChaosStages` |
| [ChaosTriggers](-chaos-triggers/index.md) | `object ChaosTriggers` |
| [SwitchTrigger](-switch-trigger/index.md) | `class SwitchTrigger : `[`Trigger`](-trigger.md)<br>Simple toggleable trigger to turn ChaosBehaviour on/off |

### Type Aliases

| Name | Summary |
|---|---|
| [Behaviour](-behaviour.md) | `typealias Behaviour = `[`Filter`](../org.http4k.core/-filter/index.md)<br>Encapsulates the type of bad behaviour to apply to the response. |
| [Stage](-stage.md) | `typealias Stage = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Filter`](../org.http4k.core/-filter/index.md)`?`<br>Defines a periodic element during which a particular ChaosBehaviour is active. |
| [Trigger](-trigger.md) | `typealias Trigger = (req: `[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.fasterxml.jackson.databind.JsonNode](com.fasterxml.jackson.databind.-json-node/index.md) |  |
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [CHAOS](-c-h-a-o-s.md) | `val `[`Header`](../org.http4k.lens/-header/index.md)`.CHAOS: `[`BiDiLens`](../org.http4k.lens/-bi-di-lens/index.md)`<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [appliedWhen](applied-when.md) | `fun `[`Behaviour`](-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](-trigger.md)`): `[`Stage`](-stage.md) |
