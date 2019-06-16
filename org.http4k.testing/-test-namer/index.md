[http4k](../../index.md) / [org.http4k.testing](../index.md) / [TestNamer](./index.md)

# TestNamer

`interface TestNamer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/TestNamer.kt#L8)

Provides the identification of test case.

### Functions

| Name | Summary |
|---|---|
| [nameFor](name-for.md) | `abstract fun nameFor(testClass: `[`Class`](https://docs.oracle.com/javase/9/docs/api/java/lang/Class.html)`<*>, testMethod: `[`Method`](https://docs.oracle.com/javase/9/docs/api/java/lang/reflect/Method.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ClassAndMethod](-class-and-method.md) | `val ClassAndMethod: `[`TestNamer`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
