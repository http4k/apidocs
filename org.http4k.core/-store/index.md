[http4k](../../index.md) / [org.http4k.core](../index.md) / [Store](./index.md)

# Store

`interface Store<OUT> : `[`LensInjector`](../../org.http4k.lens/-lens-injector/index.md)`<OUT, `[`Request`](../-request/index.md)`>, `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../-request/index.md)`, OUT>`

### Functions

| Name | Summary |
|---|---|
| [remove](remove.md) | `abstract fun remove(value: OUT): OUT?` |

### Inheritors

| Name | Summary |
|---|---|
| [RequestContexts](../-request-contexts/index.md) | In-memory RequestContext store.`class RequestContexts : `[`Store`](./index.md)`<`[`RequestContext`](../-request-context/index.md)`>` |
