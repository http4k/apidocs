[http4k](../../index.md) / [org.http4k.filter](../index.md) / [JacksonXmlGenerateXmlDataClasses](./index.md)

# JacksonXmlGenerateXmlDataClasses

`object JacksonXmlGenerateXmlDataClasses` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson-xml/src/main/kotlin/org/http4k/filter/JacksonXmlGenerateXmlDataClasses.kt#L11)

Provides an implementation of GenerateXmlDataClasses using GSON as an engine.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: `[`PrintStream`](http://docs.oracle.com/javase/6/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { Math.abs(Random().nextInt()) }): `[`GenerateXmlDataClasses`](../-generate-xml-data-classes/index.md)`<JsonNode>` |
