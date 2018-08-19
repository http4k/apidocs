[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicies](./index.md)

# ChaosPolicies

`object ChaosPolicies` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L38)

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](../-chaos-policy.md)<br>Applies to every transaction. |
| [Once](-once/index.md) | `object Once`<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [Only](-only/index.md) | `object Only`<br>Application predicated on the ChaosTrigger |
| [PercentageBased](-percentage-based/index.md) | `object PercentageBased`<br>Applies n% of the time, based on result of a Random. |
