[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [ApiRenderer](index.md) / [Auto](./-auto.md)

# Auto

`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Auto(json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`<NODE>, schema: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE> = AutoJsonToJsonSchema(json)): `[`ApiRenderer`](index.md)`<T, NODE>`

ApiRenderer which uses auto-marshalling JSON to create JSON schema for message models.

