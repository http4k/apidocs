[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosTriggers](./index.md)

# ChaosTriggers

`object ChaosTriggers`

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | Applies to every transaction.`object Always` |
| [Countdown](-countdown/index.md) | Activates for a maximum number of calls.`object Countdown` |
| [Deadline](-deadline/index.md) | Activates after a particular instant in time.`object Deadline` |
| [Delay](-delay/index.md) | Activates after a particular delay (compared to instantiation).`object Delay` |
| [MatchRequest](-match-request/index.md) | Activates when matching attributes of a single received request are met.`object MatchRequest` |
| [Once](-once/index.md) | Single application predicated on the ChaosTrigger. Further matches don't apply`object Once` |
| [PercentageBased](-percentage-based/index.md) | Applies n% of the time, based on result of a Random.`object PercentageBased` |
