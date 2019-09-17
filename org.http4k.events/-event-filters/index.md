[http4k](../../index.md) / [org.http4k.events](../index.md) / [EventFilters](./index.md)

# EventFilters

`object EventFilters` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/events/EventFilters.kt#L9)

Useful EventFilters used in building event processing pipelines to add various types of metadata to the events

### Functions

| Name | Summary |
|---|---|
| [AddTimestamp](-add-timestamp.md) | `fun AddTimestamp(clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)`): `[`EventFilter`](../-event-filter/index.md)<br>Adds timestamp metadata to the event. |
| [AddZipkinTraces](-add-zipkin-traces.md) | `fun AddZipkinTraces(): `[`EventFilter`](../-event-filter/index.md)<br>Adds Zipkin traces metadata to the event. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
