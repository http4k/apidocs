[http4k](../../index.md) / [org.http4k.traffic](../index.md) / [ReadWriteStream](index.md) / [Disk](./-disk.md)

# Disk

`fun Disk(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ".", shouldStore: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): `[`ReadWriteStream`](index.md)

Serialise and replay HTTP traffic to/from the FS in order.

