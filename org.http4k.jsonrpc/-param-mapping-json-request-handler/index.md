[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [ParamMappingJsonRequestHandler](./index.md)

# ParamMappingJsonRequestHandler

`class ParamMappingJsonRequestHandler<ROOT : `[`NODE`](index.md#NODE)`, NODE, IN, OUT> : `[`RequestHandler`](../-request-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/RequestHandler.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ParamMappingJsonRequestHandler(json: `[`Json`](../../org.http4k.format/-json/index.md)`<`[`ROOT`](index.md#ROOT)`, `[`NODE`](index.md#NODE)`>, paramsFieldNames: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, paramsLens: `[`Params`](../-params/index.md)`<`[`NODE`](index.md#NODE)`, `[`IN`](index.md#IN)`>, function: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT)`, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](index.md#OUT)`, `[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`NODE`](index.md#NODE)`): `[`NODE`](index.md#NODE) |
