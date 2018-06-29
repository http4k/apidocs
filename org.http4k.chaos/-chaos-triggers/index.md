[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosTriggers](./index.md)

# ChaosTriggers

`object ChaosTriggers` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L11)

### Functions

| Name | Summary |
|---|---|
| [Deadline](-deadline.md) | `fun Deadline(endTime: Instant, clock: Clock = Clock.systemUTC()): `[`ChaosTrigger`](../-chaos-trigger.md)<br>Activates after a particular instant in time. |
| [Delay](-delay.md) | `fun Delay(period: Duration, clock: Clock = Clock.systemUTC()): `[`ChaosTrigger`](../-chaos-trigger.md)<br>Activates after a particular delay (compared to instantiation). |
