[http4k](../index.md) / [org.http4k.chaos](./index.md)

## Package org.http4k.chaos

### Types

| Name | Summary |
|---|---|
| [ChaosBehaviour](-chaos-behaviour/index.md) | `interface ChaosBehaviour`<br>Encapsulates the type of bad behaviour to apply to the response. |
| [ChaosConfig](-chaos-config/index.md) | `object ChaosConfig`<br>Handy ways to inject configuration for ChaosBehaviours into your apps. |
| [ChaosPolicy](-chaos-policy/index.md) | `interface ChaosPolicy`<br>Determines whether or not to apply a particular type of ChaosBehaviour to a request/response. |
| [ChaosStage](-chaos-stage/index.md) | `interface ChaosStage`<br>Defines a periodic element during which a particular ChaosBehaviour is active. |
| [ChaosStageTriggers](-chaos-stage-triggers/index.md) | `object ChaosStageTriggers` |

### Type Aliases

| Name | Summary |
|---|---|
| [ChaosStageTrigger](-chaos-stage-trigger.md) | `typealias ChaosStageTrigger = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Properties

| Name | Summary |
|---|---|
| [CHAOS](-c-h-a-o-s.md) | `val `[`Common`](../org.http4k.lens/-header/-common/index.md)`.CHAOS: `[`BiDiLens`](../org.http4k.lens/-bi-di-lens/index.md)`<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
