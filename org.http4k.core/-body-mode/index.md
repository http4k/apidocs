[http4k](../../index.md) / [org.http4k.core](../index.md) / [BodyMode](./index.md)

# BodyMode

`sealed class BodyMode : (`[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`) -> `[`Body`](../-body/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/BodyMode.kt#L6)

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
