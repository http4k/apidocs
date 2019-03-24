[http4k](../../index.md) / [org.http4k.contract](../index.md) / [ContractBuilder](./index.md)

# ContractBuilder

`class ContractBuilder` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L17)

### Properties

| Name | Summary |
|---|---|
| [descriptionPath](description-path.md) | `var descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [postSecurityFilter](post-security-filter.md) | `var postSecurityFilter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [preFlightExtraction](pre-flight-extraction.md) | `var preFlightExtraction: `[`PreFlightExtraction`](../-pre-flight-extraction/index.md) |
| [preSecurityFilter](pre-security-filter.md) | `var preSecurityFilter: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [renderer](renderer.md) | `var renderer: `[`ContractRenderer`](../-contract-renderer/index.md) |
| [routes](routes.md) | `var routes: `[`Appendable`](../../org.http4k.util/-appendable/index.md)`<`[`ContractRoute`](../-contract-route/index.md)`>` |
| [security](security.md) | `var security: `[`Security`](../-security/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
