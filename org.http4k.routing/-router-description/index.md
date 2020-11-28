[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RouterDescription](./index.md)

# RouterDescription

`data class RouterDescription`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RouterDescription(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, children: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterDescription`](./index.md)`> = listOf())` |

### Properties

| Name | Summary |
|---|---|
| [children](children.md) | `val children: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RouterDescription`](./index.md)`>` |
| [description](description.md) | `val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [unavailable](unavailable.md) | `val unavailable: `[`RouterDescription`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [prettify](../../org.http4k.routing.inspect/prettify.md) | `fun `[`RouterDescription`](./index.md)`.prettify(depth: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, escape: `[`EscapeMode`](../../org.http4k.routing.inspect/-escape-mode/index.md)` = Ansi): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
