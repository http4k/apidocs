[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteMetaDsl](index.md) / [returning](./returning.md)

# returning

`@JvmName("returningResponse") fun returning(vararg descriptionToResponse: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Add possible responses to this Route.

`@JvmName("returningResponseMeta") fun returning(vararg responseMetas: `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Response`](../../org.http4k.core/-response/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Add possible response metadata to this Route. A route supports multiple possible responses.

`@JvmName("returningStatus") fun returning(vararg statusesToDescriptions: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Status`](../../org.http4k.core/-status/index.md)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Add a possible response description/reason and status to this Route

`@JvmName("returningStatus") fun returning(vararg statuses: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Add possible response statuses to this Route with no example.

`@JvmName("returningStatus") fun <T> returning(status: `[`Status`](../../org.http4k.core/-status/index.md)`, body: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<T>, T>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Add an example response (using a Lens and a value) to this Route. It is also possible to pass in the definitionId
for this response body which will override the naturally generated one.

