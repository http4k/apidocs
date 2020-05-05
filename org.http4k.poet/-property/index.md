[http4k](../../index.md) / [org.http4k.poet](../index.md) / [Property](./index.md)

# Property

`class Property`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Property(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isNullable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, vararg modifiers: KModifier)`<br>`Property(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, type: TypeName, vararg modifiers: KModifier)` |

### Properties

| Name | Summary |
|---|---|
| [modifiers](modifiers.md) | `vararg val modifiers: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<out KModifier>` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [type](type.md) | `val type: TypeName` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [addParameter](add-parameter.md) | `fun Builder.addParameter(property: `[`Property`](./index.md)`): Builder` |
| [addProperty](add-property.md) | `fun Builder.addProperty(property: `[`Property`](./index.md)`): Builder` |
| [addReturnType](add-return-type.md) | `fun Builder.addReturnType(property: `[`Property`](./index.md)`): Builder` |
| [invoke](invoke.md) | `operator fun <T> invoke(isNullable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, vararg modifiers: KModifier): `[`Property`](./index.md) |
