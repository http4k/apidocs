[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [Delay](./index.md)

# Delay

`data class Delay : `[`SerializableTrigger`](../../-serializable-trigger/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L59)

Activates after a particular delay (compared to instantiation).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Delay(period: Duration, clock: Clock = Clock.systemUTC())``Delay(endTime: Instant)`<br>Activates after a particular delay (compared to instantiation). |

### Properties

| Name | Summary |
|---|---|
| [endTime](end-time.md) | `val endTime: Instant` |

### Inherited Properties

| Name | Summary |
|---|---|
| [type](../../-serializable-trigger/type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(clock: Clock): `[`ChaosTrigger`](../../-chaos-trigger.md) |
