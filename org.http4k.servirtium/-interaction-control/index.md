[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionControl](./index.md)

# InteractionControl

`interface InteractionControl`

### Functions

| Name | Summary |
|---|---|
| [addNote](add-note.md) | `abstract fun addNote(note: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [NoOp](-no-op.md) | `val NoOp: <ERROR CLASS>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [StorageBased](-storage-based.md) | `fun StorageBased(storage: `[`InteractionStorage`](../-interaction-storage/index.md)`): <ERROR CLASS>` |

### Inheritors

| Name | Summary |
|---|---|
| [ServirtiumServer](../-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](./index.md) |
