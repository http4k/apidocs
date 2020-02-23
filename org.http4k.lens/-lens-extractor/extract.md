[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensExtractor](index.md) / [extract](./extract.md)

# extract

`open fun extract(target: IN): OUT`

Lens operation to get the value from the target. Synonym for invoke(IN)

### Exceptions

`LensFailure` - if the value could not be retrieved from the target (missing/invalid etc)