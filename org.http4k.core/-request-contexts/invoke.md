[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContexts](index.md) / [invoke](./invoke.md)

# invoke

`fun invoke(target: `[`Request`](../-request/index.md)`): `[`RequestContext`](../-request-context/index.md)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)`fun <R : `[`Request`](../-request/index.md)`> invoke(value: `[`RequestContext`](../-request-context/index.md)`, target: R): R`

Lens operation to set the value into the target

