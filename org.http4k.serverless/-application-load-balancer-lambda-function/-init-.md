[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApplicationLoadBalancerLambdaFunction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`ApplicationLoadBalancerLambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`
`ApplicationLoadBalancerLambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)``ApplicationLoadBalancerLambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)`

This is the main entry point for lambda invocations coming from an Application LoadBalancer.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

