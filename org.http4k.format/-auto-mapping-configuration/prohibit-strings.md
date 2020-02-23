[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMappingConfiguration](index.md) / [prohibitStrings](./prohibit-strings.md)

# prohibitStrings

`open fun prohibitStrings(): `[`AutoMappingConfiguration`](index.md)`<BUILDER>`

Prevent the unmarshalling of raw (unbounded) strings. Useful when we are taking data from the Internet and want
to ensure that all inbound fields are represented by bounded or validated types.

