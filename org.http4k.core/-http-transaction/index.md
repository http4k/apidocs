[http4k](../../index.md) / [org.http4k.core](../index.md) / [HttpTransaction](./index.md)

# HttpTransaction

`data class HttpTransaction`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpTransaction(request: `[`Request`](../-request/index.md)`, response: `[`Response`](../-response/index.md)`, duration: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`, labels: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = when {
        response is RoutedResponse -> mapOf(ROUTING_GROUP_LABEL to response.xUriTemplate.toString())
        request is RoutedRequest -> mapOf(ROUTING_GROUP_LABEL to request.xUriTemplate.toString())
        else -> emptyMap()
    })` |

### Properties

| Name | Summary |
|---|---|
| [duration](duration.md) | `val duration: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html) |
| [labels](labels.md) | `val labels: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [request](request.md) | `val request: `[`Request`](../-request/index.md) |
| [response](response.md) | `val response: `[`Response`](../-response/index.md) |
| [routingGroup](routing-group.md) | `val routingGroup: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [label](label.md) | `fun label(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpTransaction`](./index.md)<br>`fun label(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
