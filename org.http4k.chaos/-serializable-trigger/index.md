[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SerializableTrigger](./index.md)

# SerializableTrigger

`abstract class SerializableTrigger` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L46)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SerializableTrigger(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [type](type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(clock: Clock = Clock.systemUTC()): `[`ChaosTrigger`](../-chaos-trigger.md) |
