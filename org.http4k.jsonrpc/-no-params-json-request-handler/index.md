[http4k](../../index.md) / [org.http4k.jsonrpc](../index.md) / [NoParamsJsonRequestHandler](./index.md)

# NoParamsJsonRequestHandler

`class NoParamsJsonRequestHandler<NODE, OUT> : `[`RequestHandler`](../-request-handler.md)`<`[`NODE`](index.md#NODE)`, `[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/RequestHandler.kt#L32)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `NoParamsJsonRequestHandler(function: () -> `[`OUT`](index.md#OUT)`, resultLens: `[`Result`](../-result/index.md)`<`[`OUT`](index.md#OUT)`, `[`NODE`](index.md#NODE)`>)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`NODE`](index.md#NODE)`): `[`NODE`](index.md#NODE) |
