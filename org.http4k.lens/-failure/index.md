[http4k](../../index.md) / [org.http4k.lens](../index.md) / [Failure](./index.md)

# Failure

`sealed class Failure`

### Types

| Name | Summary |
|---|---|
| [Type](-type/index.md) | `enum class Type` |

### Properties

| Name | Summary |
|---|---|
| [meta](meta.md) | `abstract val meta: `[`Meta`](../-meta/index.md) |
| [type](type.md) | `val type: Type` |

### Inheritors

| Name | Summary |
|---|---|
| [Invalid](../-invalid/index.md) | `data class Invalid : `[`Failure`](./index.md) |
| [Missing](../-missing/index.md) | `data class Missing : `[`Failure`](./index.md) |
| [Unsupported](../-unsupported/index.md) | `data class Unsupported : `[`Failure`](./index.md) |
