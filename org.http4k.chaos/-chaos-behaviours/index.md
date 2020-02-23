[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviours](./index.md)

# ChaosBehaviours

`object ChaosBehaviours`

### Types

| Name | Summary |
|---|---|
| [BlockThread](-block-thread/index.md) | Blocks the current thread.`object BlockThread` |
| [EatMemory](-eat-memory/index.md) | Allocates memory in a busy loop until an OOM occurs.`object EatMemory` |
| [KillProcess](-kill-process/index.md) | System exits from the process.`object KillProcess` |
| [Latency](-latency/index.md) | Blocks the thread for a random amount of time within the allocated range.`object Latency` |
| [NoBody](-no-body/index.md) | Strips the entire body from a response.`object NoBody` |
| [None](-none/index.md) | Does absolutely nothing.`object None` |
| [ReturnStatus](-return-status/index.md) | Returns an empty response with the appropriate status.`object ReturnStatus` |
| [SnipBody](-snip-body/index.md) | Strips the body from a response to a particular length.`object SnipBody` |
| [SnipRequestBody](-snip-request-body/index.md) | Strips the body from a request to a particular length.`object SnipRequestBody` |
| [StackOverflow](-stack-overflow/index.md) | Allocates memory in a busy loop until an OOM occurs.`object StackOverflow` |
| [ThrowException](-throw-exception/index.md) | Throws the appropriate exception.`object ThrowException` |
| [Variable](-variable/index.md) | Provide a means of modifying a ChaosBehaviour at runtime.`class Variable : `[`Behaviour`](../-behaviour.md) |
