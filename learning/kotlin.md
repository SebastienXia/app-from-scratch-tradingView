<img src="imagesRes/kotlinImage.png">

# Kotlin Language - Learning journey-notes

## Variables
There are two types of variables, **val** and **var** :
| Type | Description | Example |
|-------|-----|------|
| val | `val`, a variable type which, like `final` in Java, is immutable and therefore cannot be modified after it has been given its first value. | `val id = "123@idsecret"` |
| var | `var` is the type of variable called mutable, which can be modified. | `var fruit = "Apple"` |

source : [Variables﻿](https://kotlinlang.org/docs/basic-syntax.html#variables)
## Types value
### Numbers
| Type | Information | Example |
|-----|-----|-----|
|Byte|8 bits *[-128 ; 127]*|`val smallNumber: Byte = 1`|
|Short|16 bits *[-32_768 : 32_767]*|`val shortNumber: Short = 1`|
|Int|32 bits *[-2_147_483_648 ; 2_147_483_647]*|`val intNumber: Int = 1`|
|Long|64 bits *[-9_223_372_036_854_775_808 ; 9_223_372_036_854_775_807]*|`val longNumber: Long = 1`|

> Note: We use the most of the time the `Int` type, moreover you'll see that all types are **C**apitalize.

## Decimal Numbers
| Type | Information | Example |
|-----|-----|-----|
|Float|32 bits, less precise than `Double`, do not forget the **f or F** at the end of the number| `val floatNumber: Float = 1.0**f**` - `output 1.0f`|
|Double|64 bits, more precise use, [use this one in your code, recommended]| `val doubleNumber: Double = 12` `output 12.0`| 

## Logic
| Type | Information | Example |
|-----|-----|-----|
|Boolean| `true` or `false`|`var logic: Boolean = false`|

## Text
| Type | Information | Example |
|-----|-----|-----|
|Char|Only on character (Unicode), single `'`|`var charValue: Char = 'A'`|
|String|indexed value, start at 0, double `"`|`var stringValue: String = "Hello"`|

## Collections
| Type | Information | Example |
|-----|-----|-----|
|Array<T>|An array is a data structure that holds a fixed number of values of the same type or its subtypes.|`val listeFruit: Array<Typr> = arrayOf(..someFruits..)`|
|List<T>|
