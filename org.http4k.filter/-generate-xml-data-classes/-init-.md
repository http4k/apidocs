[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GenerateXmlDataClasses](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`GenerateXmlDataClasses(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>, xml: `[`AutoMarshallingXml`](../../org.http4k.format/-auto-marshalling-xml/index.md)`, out: `[`PrintStream`](https://docs.oracle.com/javase/9/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { Math.abs(java.util.Random().nextInt()) })`

This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce
the number of class definitions by selecting the definition with the most fields (for cases where lists of items
have different fields).

