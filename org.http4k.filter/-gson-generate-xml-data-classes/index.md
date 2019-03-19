[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GsonGenerateXmlDataClasses](./index.md)

# GsonGenerateXmlDataClasses

`object GsonGenerateXmlDataClasses` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-xml/src/main/kotlin/org/http4k/filter/GsonGenerateXmlDataClasses.kt#L11)

Provides an implementation of GenerateXmlDataClasses using GSON as an engine.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: `[`PrintStream`](http://docs.oracle.com/javase/6/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { Math.abs(Random().nextInt()) }): `[`GenerateXmlDataClasses`](../-generate-xml-data-classes/index.md)`<JsonElement>` |
