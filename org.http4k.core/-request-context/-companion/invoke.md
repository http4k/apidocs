[http4k](../../../index.md) / [org.http4k.core](../../index.md) / [RequestContext](../index.md) / [Companion](index.md) / [invoke](./invoke.md)

# invoke

`fun <R : `[`Request`](../../-request/index.md)`> invoke(value: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`, target: R): R`

Lens operation to set the value into the target

`fun invoke(target: `[`Request`](../../-request/index.md)`): `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)