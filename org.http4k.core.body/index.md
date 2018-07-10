[http4k](../index.md) / [org.http4k.core.body](./index.md)

## Package org.http4k.core.body

### Type Aliases

| Name | Summary |
|---|---|
| [Form](-form.md) | `typealias Form = `[`Parameters`](../org.http4k.core/-parameters.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.collections.List](kotlin.collections.-list/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [form](form.md) | `fun `[`Request`](../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Returns the first form parameter with [name](form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).`fun `[`Request`](../org.http4k.core/-request/index.md)`.form(): `[`Form`](-form.md)<br>`fun `[`Request`](../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../org.http4k.core/-request/index.md) |
| [formAsMap](form-as-map.md) | `fun `[`Request`](../org.http4k.core/-request/index.md)`.formAsMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>>` |
