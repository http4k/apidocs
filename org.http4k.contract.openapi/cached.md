[http4k](../index.md) / [org.http4k.contract.openapi](index.md) / [cached](./cached.md)

# cached

`fun <API : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`ApiRenderer`](-api-renderer/index.md)`<`[`API`](cached.md#API)`, `[`NODE`](cached.md#NODE)`>.cached(): `[`ApiRenderer`](-api-renderer/index.md)`<`[`API`](cached.md#API)`, `[`NODE`](cached.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/ApiRenderer.kt#L28)

Cache the result of the API render, in case it is expensive to calculate.

