[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [RecordingControl](./index.md)

# RecordingControl

`interface RecordingControl` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/RecordingControl.kt#L5)

### Types

| Name | Summary |
|---|---|
| [NoOp](-no-op/index.md) | `object NoOp : `[`RecordingControl`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [addNote](add-note.md) | `abstract fun addNote(note: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Disk](-disk.md) | `fun Disk(file: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`): `[`RecordingControl`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [NoOp](-no-op/index.md) | `object NoOp : `[`RecordingControl`](./index.md) |
