[http4k](../index.md) / [org.http4k.jsonrpc](index.md) / [RequestHandler](./-request-handler.md)

# RequestHandler

`typealias RequestHandler<IN, OUT> = (`[`IN`](-request-handler.md#IN)`) -> `[`OUT`](-request-handler.md#OUT) [(source)](https://github.com/http4k/http4k/blob/master/http4k-jsonrpc/src/main/kotlin/org/http4k/jsonrpc/RequestHandler.kt#L6)

### Inheritors

| Name | Summary |
|---|---|
| [NoParamsJsonRequestHandler](-no-params-json-request-handler/index.md) | `class NoParamsJsonRequestHandler<NODE, OUT> : `[`RequestHandler`](./-request-handler.md)`<`[`NODE`](-no-params-json-request-handler/index.md#NODE)`, `[`NODE`](-no-params-json-request-handler/index.md#NODE)`>` |
| [ParamMappingJsonRequestHandler](-param-mapping-json-request-handler/index.md) | `class ParamMappingJsonRequestHandler<ROOT : `[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`, NODE, IN, OUT> : `[`RequestHandler`](./-request-handler.md)`<`[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`, `[`NODE`](-param-mapping-json-request-handler/index.md#NODE)`>` |
