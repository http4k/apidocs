[http4k](../../index.md) / [org.http4k.events](../index.md) / [EventFilters](./index.md)

# EventFilters

`object EventFilters`

Useful EventFilters used in building event processing pipelines to add various types of metadata to the events

### Functions

| Name | Summary |
|---|---|
| [AddTimestamp](-add-timestamp.md) | Adds timestamp metadata to the event.`fun AddTimestamp(clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): <ERROR CLASS>` |
| [AddZipkinTraces](-add-zipkin-traces.md) | Adds Zipkin traces metadata to the event.`fun AddZipkinTraces(): <ERROR CLASS>` |

### Extension Functions

| Name | Summary |
|---|---|
| [AddOpenTelemetryTraces](../-add-open-telemetry-traces.md) | Adds OpenTelemetry traces metadata to the event.`fun `[`EventFilters`](./index.md)`.AddOpenTelemetryTraces(): <ERROR CLASS>` |
