[http4k](../../index.md) / [org.http4k.junit](../index.md) / [ServirtiumReplay](./index.md)

# ServirtiumReplay

`class ServirtiumReplay : ParameterResolver`

JUnit 5 extension for replaying HTTP traffic from disk in Servirtium format.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | JUnit 5 extension for replaying HTTP traffic from disk in Servirtium format.`ServirtiumReplay(baseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, storageProvider: `[`StorageProvider`](../../org.http4k.servirtium/-storage-provider.md)`, options: `[`InteractionOptions`](../../org.http4k.servirtium/-interaction-options/index.md)` = Defaults)` |

### Functions

| Name | Summary |
|---|---|
| [resolveParameter](resolve-parameter.md) | `fun resolveParameter(pc: ParameterContext, ec: ExtensionContext): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [supportsParameter](supports-parameter.md) | `fun supportsParameter(pc: ParameterContext, ec: ExtensionContext): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
