[http4k](../../index.md) / [org.apache.commons.fileupload.util.mime](../index.md) / [MimeUtility](index.md) / [decodeText](./decode-text.md)

# decodeText

`static fun decodeText(text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!`

Decode a string of text obtained from a mail header into its proper form. The text generally will consist of a string of tokens, some of which may be encoded using base64 encoding.

### Parameters

`text` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: The text to decode.

### Exceptions

`UnsupportedEncodingException` - if the detected encoding in the input text is not supported.

**Return**
[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: The decoded text string.

