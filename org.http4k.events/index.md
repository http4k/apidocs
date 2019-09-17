[http4k](../index.md) / [org.http4k.events](./index.md)

## Package org.http4k.events

### Types

| Name | Summary |
|---|---|
| [AutoJsonEvents](-auto-json-events/index.md) | `object AutoJsonEvents` |
| [Event](-event/index.md) | `interface Event` |
| [EventCategory](-event-category/index.md) | `data class EventCategory` |
| [EventFilters](-event-filters/index.md) | `object EventFilters`<br>Useful EventFilters used in building event processing pipelines to add various types of metadata to the events |
| [EventsFilter](-events-filter/index.md) | `interface EventsFilter : (`[`Events`](-events.md)`) -> `[`Events`](-events.md) |
| [MetadataEvent](-metadata-event/index.md) | `class MetadataEvent : `[`Event`](-event/index.md) |

### Type Aliases

| Name | Summary |
|---|---|
| [Events](-events.md) | `typealias Events = (`[`Event`](-event/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [plus](plus.md) | `operator fun `[`Event`](-event/index.md)`.plus(that: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>): `[`Event`](-event/index.md)<br>Attach some metadata to this event |
| [then](then.md) | `fun `[`EventsFilter`](-events-filter/index.md)`.then(next: `[`EventsFilter`](-events-filter/index.md)`): `[`EventsFilter`](-events-filter/index.md)<br>`fun `[`EventsFilter`](-events-filter/index.md)`.then(next: `[`Events`](-events.md)`): `[`Events`](-events.md) |
