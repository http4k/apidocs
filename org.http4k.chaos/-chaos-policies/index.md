[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicies](./index.md)

# ChaosPolicies

`object ChaosPolicies` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L26)

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](../-chaos-policy/index.md)<br>Applies to every transaction. |
| [Once](-once/index.md) | `data class Once : `[`ChaosPolicy`](../-chaos-policy/index.md)<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [Only](-only/index.md) | `data class Only : `[`ChaosPolicy`](../-chaos-policy/index.md)<br>Application predicated on the ChaosTrigger |
| [PercentageBased](-percentage-based/index.md) | `data class PercentageBased : `[`ChaosPolicy`](../-chaos-policy/index.md)<br>Applies n% of the time, based on result of a Random. |
