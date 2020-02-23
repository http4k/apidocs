[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ClientFilters](../index.md) / [GZip](./index.md)

# GZip

`object GZip`

Basic GZip and Gunzip support of Request/Response.
Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip'

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = Memory): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
