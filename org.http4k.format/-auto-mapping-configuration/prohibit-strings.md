[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMappingConfiguration](index.md) / [prohibitStrings](./prohibit-strings.md)

# prohibitStrings

`open fun prohibitStrings(): `[`AutoMappingConfiguration`](index.md)`<`[`BUILDER`](index.md#BUILDER)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMappingConfiguration.kt#L36)

Prevent the unmarshalling of raw (unbounded) strings. Useful when we are taking data from the Internet and want
to ensure that all inbound fields are represented by bounded or validated types.

