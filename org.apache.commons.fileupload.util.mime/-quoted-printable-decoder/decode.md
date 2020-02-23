[http4k](../../index.md) / [org.apache.commons.fileupload.util.mime](../index.md) / [QuotedPrintableDecoder](index.md) / [decode](./decode.md)

# decode

`static fun decode(data: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`!, out: `[`OutputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Decode the encoded byte data writing it to the given output stream.

### Parameters

`data` - [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)!: The array of byte data to decode.

`out` - [OutputStream](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html)!: The output stream used to return the decoded data.

### Exceptions

`IOException` - if an error occurs