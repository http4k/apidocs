[http4k](../../index.md) / [org.http4k.contract.openapi](../index.md) / [ApiRenderer](index.md) / [Auto](./-auto.md)

# Auto

`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Auto(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](-auto.md#NODE)`>, schema: `[`JsonSchemaCreator`](../../org.http4k.util/-json-schema-creator/index.md)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, `[`NODE`](-auto.md#NODE)`> = AutoJsonToJsonSchema(json)): `[`ApiRenderer`](index.md)`<`[`T`](-auto.md#T)`, `[`NODE`](-auto.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/openapi/ApiRenderer.kt#L20)

ApiRenderer which uses auto-marshalling JSON to create JSON schema for message models.

