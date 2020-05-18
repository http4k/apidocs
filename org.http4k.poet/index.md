[http4k](../index.md) / [org.http4k.poet](./index.md)

## Package org.http4k.poet

### Types

| Name | Summary |
|---|---|
| [Property](-property/index.md) | `class Property` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.squareup.kotlinpoet.ClassName](com.squareup.kotlinpoet.-class-name/index.md) |  |
| [com.squareup.kotlinpoet.FileSpec.Builder](com.squareup.kotlinpoet.-file-spec.-builder/index.md) |  |
| [com.squareup.kotlinpoet.FunSpec.Builder](com.squareup.kotlinpoet.-fun-spec.-builder/index.md) |  |
| [kotlin.reflect.KClass](kotlin.reflect.-k-class/index.md) |  |
| [kotlin.String](kotlin.-string/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [lensSpecClazz](lens-spec-clazz.md) | `val `[`ParameterSpec`](../org.http4k.openapi.v3/-parameter-spec/index.md)`.lensSpecClazz: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<out `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [asTypeName](as-type-name.md) | `fun `[`ParameterSpec`](../org.http4k.openapi.v3/-parameter-spec/index.md)`.asTypeName(): TypeName?` |
| [lensConstruct](lens-construct.md) | `fun `[`ParameterSpec`](../org.http4k.openapi.v3/-parameter-spec/index.md)`.lensConstruct(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [lensDeclaration](lens-declaration.md) | `fun `[`NamedSchema`](../org.http4k.openapi/-named-schema/index.md)`.lensDeclaration(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): CodeBlock?` |
| [lensDeclarations](lens-declarations.md) | `fun `[`PathV3`](../org.http4k.openapi.v3/-path-v3/index.md)`.lensDeclarations(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
| [member](member.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> member(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): MemberName` |
| [packageMember](package-member.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> packageMember(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): MemberName` |
| [quotedName](quoted-name.md) | `fun `[`ParameterSpec`](../org.http4k.openapi.v3/-parameter-spec/index.md)`.quotedName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
