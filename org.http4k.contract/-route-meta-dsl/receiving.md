[http4k](../../index.md) / [org.http4k.contract](../index.md) / [RouteMetaDsl](index.md) / [receiving](./receiving.md)

# receiving

`fun <T> receiving(body: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`T`](receiving.md#T)`>, `[`T`](receiving.md#T)`>, definitionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L92)

Add an example request (using a Lens and a value) to this Route. It is also possible to pass in the definitionId
for this request body which will override the naturally generated one.

`fun receiving(requestMeta: `[`HttpMessageMeta`](../-http-message-meta/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L100)

Add request metadata to this Route. A route only supports a single possible request.

`fun <T> receiving(bodyLens: `[`BiDiBodyLens`](../../org.http4k.lens/-bi-di-body-lens/index.md)`<`[`T`](receiving.md#T)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/routeMeta.kt#L109)

Set the input body type for this request WITHOUT an example. Hence the content-type will be registered but no
example schema will be generated.

