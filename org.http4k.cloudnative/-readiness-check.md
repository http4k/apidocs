[http4k](../index.md) / [org.http4k.cloudnative](index.md) / [ReadinessCheck](./-readiness-check.md)

# ReadinessCheck

`typealias ReadinessCheck = () -> `[`ReadinessCheckResult`](-readiness-check-result/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/ReadinessCheckResult.kt#L7)

A Readiness check is used by K8S to determine if the pod is ready to receive traffic. An example is to test
if the app can talk to it's database.

