[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviour](./index.md)

# ChaosBehaviour

`interface ChaosBehaviour` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviour.kt#L13)

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [inject](inject.md) | `open fun inject(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>`open fun inject(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [BlockThread](-block-thread.md) | `fun BlockThread(): `[`ChaosBehaviour`](./index.md) |
| [ExtraLatencyFromEnv](-extra-latency-from-env.md) | `fun ExtraLatencyFromEnv(): `[`ChaosBehaviour`](./index.md) |
| [KillProcess](-kill-process.md) | `fun KillProcess(): `[`ChaosBehaviour`](./index.md) |
| [Latency](-latency.md) | `fun Latency(minDelay: Duration, maxDelay: Duration): `[`ChaosBehaviour`](./index.md) |
| [ReturnStatus](-return-status.md) | `fun ReturnStatus(status: `[`Status`](../../org.http4k.core/-status/index.md)` = INTERNAL_SERVER_ERROR): `[`ChaosBehaviour`](./index.md) |
| [ThrowException](-throw-exception.md) | `fun ThrowException(e: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)` = ChaosException("Chaos behaviour injected!")): `[`ChaosBehaviour`](./index.md) |
