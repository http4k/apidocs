[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionControl](./index.md)

# InteractionControl

`interface InteractionControl`

Provides controls for interacting with an in-action Interaction recording.

### Types

| Name | Summary |
|---|---|
| [NoOp](-no-op/index.md) | `object NoOp : `[`InteractionControl`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [addNote](add-note.md) | `abstract fun addNote(note: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [StorageBased](-storage-based.md) | `fun StorageBased(storage: `[`InteractionStorage`](../-interaction-storage/index.md)`): `[`InteractionControl`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ServirtiumServer](../-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](./index.md) |
