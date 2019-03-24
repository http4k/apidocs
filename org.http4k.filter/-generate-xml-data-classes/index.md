[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GenerateXmlDataClasses](./index.md)

# GenerateXmlDataClasses

`class GenerateXmlDataClasses<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Filter`](../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/GenerateXmlDataClasses.kt#L16)

This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce
the number of class definitions by selecting the definition with the most fields (for cases where lists of items
have different fields).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GenerateXmlDataClasses(json: `[`JsonLibAutoMarshallingJson`](../../org.http4k.format/-json-lib-auto-marshalling-json/index.md)`<`[`NODE`](index.md#NODE)`>, xml: `[`AutoMarshallingXml`](../../org.http4k.format/-auto-marshalling-xml/index.md)`, out: `[`PrintStream`](https://docs.oracle.com/javase/6/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { Math.abs(java.util.Random().nextInt()) })`<br>This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(p1: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
