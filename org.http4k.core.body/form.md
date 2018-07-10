[http4k](../index.md) / [org.http4k.core.body](index.md) / [form](./form.md)

# form

`fun `[`Request`](../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/body/FormBody.kt#L12)

Returns the first form parameter with [name](form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).

Use [formAsMap](form-as-map.md) if you don't want to decode the body every invocation.

`fun `[`Request`](../org.http4k.core/-request/index.md)`.form(): `[`Form`](-form.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/body/FormBody.kt#L18)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../org.http4k.core/-request/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/body/FormBody.kt#L20)