[http4k](../../index.md) / [org.http4k.core](../index.md) / [HttpMessage](index.md) / [close](./close.md)

# close

`open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Closes the request. For server generated messages, this is called by all backend/client implementations,
but when consuming external responses in streaming mode, this should be used.

