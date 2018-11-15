[http4k](../../index.md) / [org.http4k.filter](../index.md) / [SamplingDecision](./index.md)

# SamplingDecision

`data class SamplingDecision` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ZipkinTraces.kt#L29)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SamplingDecision(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [value](value.md) | `val value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [DO_NOT_SAMPLE](-d-o_-n-o-t_-s-a-m-p-l-e.md) | `val DO_NOT_SAMPLE: `[`SamplingDecision`](./index.md) |
| [SAMPLE](-s-a-m-p-l-e.md) | `val SAMPLE: `[`SamplingDecision`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [from](from.md) | `fun from(sampledHeaderValue: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`SamplingDecision`](./index.md) |
