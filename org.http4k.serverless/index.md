[http4k](../index.md) / [org.http4k.serverless](./index.md)

## Package org.http4k.serverless

Common code relevant to HTTP serverless implementations.

### Types

| Name | Summary |
|---|---|
| [ApiGatewayV1LambdaFunction](-api-gateway-v1-lambda-function/index.md) | This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApiGatewayV1LambdaFunction : `[`AwsLambdaFunction`](-aws-lambda-function.md)`<APIGatewayProxyRequestEvent, APIGatewayProxyResponseEvent>` |
| [ApiGatewayV2LambdaFunction](-api-gateway-v2-lambda-function/index.md) | This is the main entry point for lambda invocations using the V2 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApiGatewayV2LambdaFunction : `[`AwsLambdaFunction`](-aws-lambda-function.md)`<APIGatewayV2HTTPEvent, APIGatewayV2HTTPResponse>` |
| [ApplicationLoadBalancerLambdaFunction](-application-load-balancer-lambda-function/index.md) | This is the main entry point for lambda invocations coming from an Application LoadBalancer. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApplicationLoadBalancerLambdaFunction : `[`AwsLambdaFunction`](-aws-lambda-function.md)`<ApplicationLoadBalancerRequestEvent, ApplicationLoadBalancerResponseEvent>` |
| [AppLoader](-app-loader.md) | `interface AppLoader : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [AppLoaderWithContexts](-app-loader-with-contexts.md) | `interface AppLoaderWithContexts : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, `[`RequestContexts`](../org.http4k.core/-request-contexts/index.md)`) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [AwsLambdaFunction](-aws-lambda-function.md) | `abstract class AwsLambdaFunction<Req : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, Resp> : RequestHandler<Req, Resp>` |
| [BootstrapAppLoader](-bootstrap-app-loader/index.md) | `object ~~BootstrapAppLoader~~ : `[`AppLoaderWithContexts`](-app-loader-with-contexts.md) |
| [DetectBinaryBody](-detect-binary-body/index.md) | OpenWhisk Base64 encodes Binary requests and responses when they are sent to the deployed Function. This interface allows for custom implementations of that logic, which might be required if your function supports more than one endpoint (with mixed request/response types).`interface DetectBinaryBody` |
| [GoogleCloudFunction](-google-cloud-function/index.md) | `open class GoogleCloudFunction : HttpFunction` |
| [LambdaFunction](-lambda-function/index.md) | This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`open class ~~LambdaFunction~~ : `[`ApiGatewayV1LambdaFunction`](-api-gateway-v1-lambda-function/index.md) |
| [OpenWhiskFunction](-open-whisk-function/index.md) | `class OpenWhiskFunction : (JsonObject) -> JsonObject` |
| [RequestContent](-request-content/index.md) | `class RequestContent` |

### Exceptions

| Name | Summary |
|---|---|
| [BootstrapException](-bootstrap-exception/index.md) | `open class BootstrapException : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [CouldNotFindAppLoaderException](-could-not-find-app-loader-exception/index.md) | `class CouldNotFindAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |
| [InvalidAppLoaderException](-invalid-app-loader-exception/index.md) | `class InvalidAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |

### Properties

| Name | Summary |
|---|---|
| [GCF_REQUEST_KEY](-g-c-f_-r-e-q-u-e-s-t_-k-e-y.md) | `const val GCF_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LAMBDA_CONTEXT_KEY](-l-a-m-b-d-a_-c-o-n-t-e-x-t_-k-e-y.md) | `const val LAMBDA_CONTEXT_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LAMBDA_REQUEST_KEY](-l-a-m-b-d-a_-r-e-q-u-e-s-t_-k-e-y.md) | `const val LAMBDA_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [OW_REQUEST_KEY](-o-w_-r-e-q-u-e-s-t_-k-e-y.md) | `const val OW_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [&lt;no name provided&gt;](-no name provided-.md) | Http4k app loader - instantiate the application from the environment config`fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [then](then.md) | `fun `[`Filter`](../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoader`](-app-loader.md)`): `[`AppLoader`](-app-loader.md)<br>`fun `[`Filter`](../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoaderWithContexts`](-app-loader-with-contexts.md)`): <ERROR CLASS>` |
