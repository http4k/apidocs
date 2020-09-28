[http4k](../index.md) / [org.http4k.events](./index.md)

## Package org.http4k.events

### Types

| Name | Summary |
|---|---|
| [AutoJsonEvents](-auto-json-events/index.md) | `object AutoJsonEvents` |
| [Event](-event/index.md) | Represents a meaningful "happening" in an app.`interface Event` |
| [EventCategory](-event-category/index.md) | `data class EventCategory` |
| [EventFilter](-event-filter/index.md) | `interface EventFilter : (`[`Events`](-events.md)`) -> `[`Events`](-events.md) |
| [EventFilters](-event-filters/index.md) | Useful EventFilters used in building event processing pipelines to add various types of metadata to the events`object EventFilters` |
| [Events](-events.md) | `typealias Events = (`[`Event`](-event/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [EventsFilter](-events-filter.md) | `typealias ~~EventsFilter~~ = `[`EventFilter`](-event-filter/index.md) |
| [MetadataEvent](-metadata-event/index.md) | `class MetadataEvent : `[`Event`](-event/index.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [&lt;no name provided&gt;](-no name provided-.md) | An EventFilter is used to create pipelines for Event processing.`fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [plus](plus.md) | Attach some metadata to this event`operator fun `[`Event`](-event/index.md)`.plus(that: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Event`](-event/index.md) |
| [then](then.md) | `fun `[`EventFilter`](-event-filter/index.md)`.then(next: `[`EventFilter`](-event-filter/index.md)`): `[`EventFilter`](-event-filter/index.md)<br>`fun `[`EventFilter`](-event-filter/index.md)`.then(next: `[`Events`](-events.md)`): `[`Events`](-events.md) |
