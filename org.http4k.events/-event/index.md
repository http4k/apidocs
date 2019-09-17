[http4k](../../index.md) / [org.http4k.events](../index.md) / [Event](./index.md)

# Event

`interface Event` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/events/events.kt#L5)

### Types

| Name | Summary |
|---|---|
| [Error](-error/index.md) | `data class Error : `[`Event`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [plus](../plus.md) | `operator fun `[`Event`](./index.md)`.plus(that: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Event`](./index.md)<br>Attach some metadata to this event |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [Error](-error/index.md) | `data class Error : `[`Event`](./index.md) |
| [MetadataEvent](../-metadata-event/index.md) | `class MetadataEvent : `[`Event`](./index.md) |
