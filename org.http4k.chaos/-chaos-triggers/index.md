[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosTriggers](./index.md)

# ChaosTriggers

`object ChaosTriggers` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L46)

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always`<br>Applies to every transaction. |
| [Countdown](-countdown/index.md) | `object Countdown`<br>Activates for a maximum number of calls. |
| [Deadline](-deadline/index.md) | `object Deadline`<br>Activates after a particular instant in time. |
| [Delay](-delay/index.md) | `object Delay`<br>Activates after a particular delay (compared to instantiation). |
| [MatchRequest](-match-request/index.md) | `object MatchRequest`<br>Activates when matching attributes of a single received request are met. |
| [Once](-once/index.md) | `object Once`<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [PercentageBased](-percentage-based/index.md) | `object PercentageBased`<br>Applies n% of the time, based on result of a Random. |
