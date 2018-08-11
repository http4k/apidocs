[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [Deadline](./index.md)

# Deadline

`data class Deadline : `[`SerializableTrigger`](../../-serializable-trigger/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L32)

Activates after a particular instant in time.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Deadline(endTime: Instant)`<br>Activates after a particular instant in time. |

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
