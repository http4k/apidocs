[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosPolicies](../index.md) / [Only](./index.md)

# Only

`data class Only : `[`ChaosPolicy`](../../-chaos-policy.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L39)

Application predicated on the ChaosTrigger

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Only(trigger: `[`ChaosTrigger`](../../-chaos-trigger.md)`)`<br>Application predicated on the ChaosTrigger |

### Properties

| Name | Summary |
|---|---|
| [trigger](trigger.md) | `val trigger: `[`ChaosTrigger`](../../-chaos-trigger.md) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
