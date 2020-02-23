[http4k](../../index.md) / [org.apache.commons.fileupload.util.mime](../index.md) / [Base64Decoder](index.md) / [decode](./decode.md)

# decode

`static fun decode(data: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`!, out: `[`OutputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Decode the base 64 encoded byte data writing it to the given output stream, whitespace characters will be ignored.

### Parameters

`data` - [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)!: the buffer containing the Base64-encoded data

`out` - [OutputStream](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html)!: the output stream to hold the decoded bytes

### Exceptions

`IOException` - thrown when the padding is incorrect or the input is truncated.