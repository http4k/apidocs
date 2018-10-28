[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [ReadinessCheck](./index.md)

# ReadinessCheck

`interface ReadinessCheck : () -> `[`ReadinessCheckResult`](../-readiness-check-result/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/ReadinessCheckResult.kt#L7)

A Readiness check is used to determine if the pod is ready to receive traffic. An example is to test
if the app can talk to it's database.

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
