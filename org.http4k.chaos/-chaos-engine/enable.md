[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](index.md) / [enable](./enable.md)

# enable

`fun enable(): `[`ChaosEngine`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L38)

Turn on Chaos Engine using the pre-initialised chaotic behaviour. Note that this may not actually produce any
effect based on the configured behaviour (e.g. if there is a specific Trigger that is condition-based.)

`fun enable(behaviour: `[`Behaviour`](../-behaviour.md)`): `[`ChaosEngine`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L43)

Update with new simple Chaotic behaviour to be applied whenever the ChaosEngine is enabled.

`fun enable(stage: `[`Stage`](../-stage.md)`): `[`ChaosEngine`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosEngine.kt#L51)

Update the new complex (multi-stage, triggers etc) Chaotic behaviour to be applied whenever the ChaosEngine is enabled.

