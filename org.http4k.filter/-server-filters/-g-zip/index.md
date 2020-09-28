[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ServerFilters](../index.md) / [GZip](./index.md)

# GZip

`object GZip`

Basic GZip and Gunzip support of Request/Response.
Only Gunzips requests which contain "transfer-encoding" header containing 'gzip'
Only Gzips responses when request contains "accept-encoding" header containing 'gzip'.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(compressionMode: `[`GzipCompressionMode`](../../-gzip-compression-mode/index.md)` = Memory): `[`Filter`](../../../org.http4k.core/-filter.md) |
