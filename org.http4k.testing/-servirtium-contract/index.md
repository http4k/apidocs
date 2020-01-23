[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ServirtiumContract](./index.md)

# ServirtiumContract

`interface ServirtiumContract` [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/testing/ServirtiumContract.kt#L9)

Defines a test contract which can be used to implement recording or replaying of Servirtium-formatted tests

### Properties

| Name | Summary |
|---|---|
| [manipulations](manipulations.md) | `open val manipulations: `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
