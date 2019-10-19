[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ZipkinTraces](./index.md)

# ZipkinTraces

`data class ZipkinTraces` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ZipkinTraces.kt#L37)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ZipkinTraces(traceId: `[`TraceId`](../-trace-id/index.md)`, spanId: `[`TraceId`](../-trace-id/index.md)`, parentSpanId: `[`TraceId`](../-trace-id/index.md)`?, samplingDecision: `[`SamplingDecision`](../-sampling-decision/index.md)` = SAMPLE)` |

### Properties

| Name | Summary |
|---|---|
| [parentSpanId](parent-span-id.md) | `val parentSpanId: `[`TraceId`](../-trace-id/index.md)`?` |
| [samplingDecision](sampling-decision.md) | `val samplingDecision: `[`SamplingDecision`](../-sampling-decision/index.md) |
| [spanId](span-id.md) | `val spanId: `[`TraceId`](../-trace-id/index.md) |
| [traceId](trace-id.md) | `val traceId: `[`TraceId`](../-trace-id/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): `[`ZipkinTraces`](./index.md)<br>`operator fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(value: `[`ZipkinTraces`](./index.md)`, target: `[`T`](invoke.md#T)`): `[`T`](invoke.md#T) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
