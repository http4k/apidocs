[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContexts](./index.md)

# RequestContexts

`class RequestContexts : `[`Store`](../-store/index.md)`<`[`RequestContext`](../-request-context/index.md)`>`

In-memory RequestContext store.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | In-memory RequestContext store.`RequestContexts()` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to get the value from the target`fun invoke(target: `[`Request`](../-request/index.md)`): `[`RequestContext`](../-request-context/index.md)<br>Lens operation to set the value into the target`fun <R : `[`Request`](../-request/index.md)`> invoke(value: `[`RequestContext`](../-request-context/index.md)`, target: R): R` |
| [remove](remove.md) | `fun remove(value: `[`RequestContext`](../-request-context/index.md)`): `[`RequestContext`](../-request-context/index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../../org.http4k.lens/as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../../org.http4k.lens/-lens-failure/index.md)`>>` |
