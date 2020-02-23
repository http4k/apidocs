[http4k](../../index.md) / [org.http4k.contract.openapi.v3](../index.md) / [FieldRetrieval](./index.md)

# FieldRetrieval

`interface FieldRetrieval : (`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Field`](../-field/index.md)

### Companion Object Functions

| Name | Summary |
|---|---|
| [compose](compose.md) | `fun compose(vararg retrieval: `[`FieldRetrieval`](./index.md)`): `[`FieldRetrieval`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [JacksonJsonNamingAnnotated](../-jackson-json-naming-annotated/index.md) | `object JacksonJsonNamingAnnotated : `[`FieldRetrieval`](./index.md) |
| [JacksonJsonPropertyAnnotated](../-jackson-json-property-annotated/index.md) | `object JacksonJsonPropertyAnnotated : `[`FieldRetrieval`](./index.md) |
| [SimpleLookup](../-simple-lookup/index.md) | `object SimpleLookup : `[`FieldRetrieval`](./index.md) |
