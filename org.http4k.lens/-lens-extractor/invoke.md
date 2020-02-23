[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](index.md) / [invoke](./invoke.md)

# invoke

`abstract operator fun invoke(target: IN): OUT`

Lens operation to get the value from the target

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)