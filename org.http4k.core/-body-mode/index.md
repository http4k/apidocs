[http4k](../../index.md) / [org.http4k.core](../index.md) / [BodyMode](./index.md)

# BodyMode

`sealed class BodyMode : (`[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`) -> `[`Body`](../-body/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/BodyMode.kt#L18)

BodyMode represents a choice between working lazily with streams or eagerly storing the body contents in memory.

This choice comes with the following trade-offs:

`Memory` does not require any special treatment. However, you need to be confident that the sum of all "in-flight"
body bytes does not exceed your JVM heap. Otherwise, you'll run into `OutOfMemoryException's.

`Stream`, on the other hand, allows you to handle payloads of any size, but you'll need to make sure that:

1. You're consuming it only once and at the right place (harder to add "debugging" filters too).
2. It's *always* consumed, or `close()` is called appropriately.

### Types

| Name | Summary |
|---|---|
| [Memory](-memory/index.md) | `object Memory : `[`BodyMode`](./index.md) |
| [Stream](-stream/index.md) | `object Stream : `[`BodyMode`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [Memory](-memory/index.md) | `object Memory : `[`BodyMode`](./index.md) |
| [Stream](-stream/index.md) | `object Stream : `[`BodyMode`](./index.md) |
