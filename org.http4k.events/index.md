[http4k](../index.md) / [org.http4k.events](./index.md)

## Package org.http4k.events

### Types

| Name | Summary |
|---|---|
| [AutoJsonEvents](-auto-json-events/index.md) | `object AutoJsonEvents` |
| [Event](-event/index.md) | `interface Event`<br>Represents a meaningful "happening" in an app. |
| [EventCategory](-event-category/index.md) | `data class EventCategory` |
| [EventFilter](-event-filter/index.md) | `interface EventFilter : (`[`Events`](-events.md)`) -> `[`Events`](-events.md)<br>An EventFilter is used to create pipelines for Event processing. |
| [EventFilters](-event-filters/index.md) | `object EventFilters`<br>Useful EventFilters used in building event processing pipelines to add various types of metadata to the events |
| [MetadataEvent](-metadata-event/index.md) | `class MetadataEvent : `[`Event`](-event/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [Events](-events.md) | `typealias Events = (`[`Event`](-event/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [EventsFilter](-events-filter.md) | `typealias ~~EventsFilter~~ = `[`EventFilter`](-event-filter/index.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [plus](plus.md) | `operator fun `[`Event`](-event/index.md)`.plus(that: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Event`](-event/index.md)<br>Attach some metadata to this event |
| [then](then.md) | `fun `[`EventFilter`](-event-filter/index.md)`.then(next: `[`EventFilter`](-event-filter/index.md)`): `[`EventFilter`](-event-filter/index.md)<br>`fun `[`EventFilter`](-event-filter/index.md)`.then(next: `[`Events`](-events.md)`): `[`Events`](-events.md) |
