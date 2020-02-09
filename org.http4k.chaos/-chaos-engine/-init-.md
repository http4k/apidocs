[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosEngine](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`ChaosEngine(behaviour: `[`Behaviour`](../-behaviour.md)`)``ChaosEngine(initialStage: `[`Stage`](../-stage.md)` = Wait)`

The Chaos Engine controls the lifecycle of applying Chaotic behaviour to traffic, which is exposed as a
standard Http4k Filter. Chaos can be programmatically updated and enabled/disabled. By default, the engine
is deactivated, so activate() needs to be called to witness any change in behaviour,

