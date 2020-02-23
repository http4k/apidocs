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
