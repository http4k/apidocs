[http4k](../index.md) / [org.http4k.serverless](index.md) / [AwsLambdaFunction](./-aws-lambda-function.md)

# AwsLambdaFunction

`abstract class AwsLambdaFunction<Req : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, Resp> : RequestHandler<Req, Resp>`

### Inheritors

| Name | Summary |
|---|---|
| [ApiGatewayV1LambdaFunction](-api-gateway-v1-lambda-function/index.md) | This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApiGatewayV1LambdaFunction : `[`AwsLambdaFunction`](./-aws-lambda-function.md)`<APIGatewayProxyRequestEvent, APIGatewayProxyResponseEvent>` |
| [ApiGatewayV2LambdaFunction](-api-gateway-v2-lambda-function/index.md) | This is the main entry point for lambda invocations using the V2 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApiGatewayV2LambdaFunction : `[`AwsLambdaFunction`](./-aws-lambda-function.md)`<APIGatewayV2HTTPEvent, APIGatewayV2HTTPResponse>` |
| [ApplicationLoadBalancerLambdaFunction](-application-load-balancer-lambda-function/index.md) | This is the main entry point for lambda invocations coming from an Application LoadBalancer. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`abstract class ApplicationLoadBalancerLambdaFunction : `[`AwsLambdaFunction`](./-aws-lambda-function.md)`<ApplicationLoadBalancerRequestEvent, ApplicationLoadBalancerResponseEvent>` |
