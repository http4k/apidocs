[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [AwsHttpAdapter](./index.md)

# AwsHttpAdapter

`interface AwsHttpAdapter<Req, Resp>`

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(req: Req, ctx: Context): `[`Request`](../../org.http4k.core/-request/index.md)<br>`abstract operator fun invoke(resp: `[`Response`](../../org.http4k.core/-response/index.md)`): Resp` |

### Inheritors

| Name | Summary |
|---|---|
| [ApiGatewayV1AwsHttpAdapter](../-api-gateway-v1-aws-http-adapter/index.md) | `object ApiGatewayV1AwsHttpAdapter : `[`AwsHttpAdapter`](./index.md)`<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>>` |
| [ApiGatewayV2AwsHttpAdapter](../-api-gateway-v2-aws-http-adapter/index.md) | `object ApiGatewayV2AwsHttpAdapter : `[`AwsHttpAdapter`](./index.md)`<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>>` |
| [ApplicationLoadBalancerAwsHttpAdapter](../-application-load-balancer-aws-http-adapter/index.md) | `object ApplicationLoadBalancerAwsHttpAdapter : `[`AwsHttpAdapter`](./index.md)`<`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>, `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>>` |
| [InvocationLambdaAwsHttpAdapter](../-invocation-lambda-aws-http-adapter/index.md) | `object InvocationLambdaAwsHttpAdapter : `[`AwsHttpAdapter`](./index.md)`<`[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`>` |
