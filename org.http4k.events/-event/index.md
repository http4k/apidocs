[http4k](../../index.md) / [org.http4k.events](../index.md) / [Event](./index.md)

# Event

`interface Event`

Represents a meaningful "happening" in an app.

### Types

| Name | Summary |
|---|---|
| [Error](-error/index.md) | `data class Error : `[`Event`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | Attach some metadata to this event`operator fun `[`Event`](./index.md)`.plus(that: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Event`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [MetadataEvent](../-metadata-event/index.md) | `class MetadataEvent : `[`Event`](./index.md) |
