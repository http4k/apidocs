[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [CleanProxy](./index.md)

# CleanProxy

`object CleanProxy` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/ClientFilters.kt#L162)

This Filter is used to clean the Request and Response when proxying directly to another system. The purpose
of this is to remove any routing metadata that we may have attached to it before sending it onwards.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
