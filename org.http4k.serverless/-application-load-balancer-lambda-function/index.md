[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApplicationLoadBalancerLambdaFunction](./index.md)

# ApplicationLoadBalancerLambdaFunction

`abstract class ApplicationLoadBalancerLambdaFunction : `[`AwsLambdaFunction`](../-aws-lambda-function.md)`<ApplicationLoadBalancerRequestEvent, ApplicationLoadBalancerResponseEvent>`

This is the main entry point for lambda invocations coming from an Application LoadBalancer.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApplicationLoadBalancerLambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`ApplicationLoadBalancerLambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>This is the main entry point for lambda invocations coming from an Application LoadBalancer. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`ApplicationLoadBalancerLambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `open fun handleRequest(req: ApplicationLoadBalancerRequestEvent, ctx: Context): ApplicationLoadBalancerResponseEvent` |
