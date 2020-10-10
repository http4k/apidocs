[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](index.md) / [GZip](./-g-zip.md)

# GZip

`fun GZip(compressionMode: `[`GzipCompressionMode`](../-gzip-compression-mode/index.md)` = Memory): `[`Filter`](../../org.http4k.core/-filter.md)

Basic GZip and Gunzip support of Request/Response.
Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip'

