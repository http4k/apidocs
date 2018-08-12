[http4k](../index.md) / [org.http4k.chaos](index.md) / [ChaosPolicy](./-chaos-policy.md)

# ChaosPolicy

`typealias ChaosPolicy = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L11)

Determines whether or not to apply a particular type of ChaosBehaviour to a request/response.

### Inheritors

| Name | Summary |
|---|---|
| [Always](-chaos-policies/-always/index.md) | `object Always : `[`ChaosPolicy`](./-chaos-policy.md)<br>Applies to every transaction. |
| [Once](-chaos-policies/-once/index.md) | `data class Once : `[`ChaosPolicy`](./-chaos-policy.md)<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [Only](-chaos-policies/-only/index.md) | `data class Only : `[`ChaosPolicy`](./-chaos-policy.md)<br>Application predicated on the ChaosTrigger |
| [PercentageBased](-chaos-policies/-percentage-based/index.md) | `data class PercentageBased : `[`ChaosPolicy`](./-chaos-policy.md)<br>Applies n% of the time, based on result of a Random. |
