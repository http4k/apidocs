[http4k](../../index.md) / [org.http4k.core](../index.md) / [Store](./index.md)

# Store

`interface Store<OUT> : `[`LensInjector`](../../org.http4k.lens/-lens-injector/index.md)`<OUT, `[`Request`](../-request/index.md)`>, `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../-request/index.md)`, OUT>`

### Functions

| Name | Summary |
|---|---|
| [remove](remove.md) | `abstract fun remove(value: OUT): OUT?` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../../org.http4k.lens/as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`>>` |

### Inheritors

| Name | Summary |
|---|---|
| [RequestContexts](../-request-contexts/index.md) | In-memory RequestContext store.`class RequestContexts : `[`Store`](./index.md)`<`[`RequestContext`](../-request-context/index.md)`>` |
