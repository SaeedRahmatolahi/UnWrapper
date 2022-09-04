# UnWrapper
Unwrap your optionals easily

## Description

UnWrapper will help you to Safely unwrap optional types.

## Supported Value Types

This extension supports most of the Swift built-in value types such as String, Int, Bool, Double, Float, Array, Dictionary, etc .
It can also check if the optional value is nil or not 

## Usage

to use UnWrapper you just need to copy the framework in your app and use `unWrap` or `unWrapOr(yourDefaultValue)`  for unWrap Optionals . or if you just want to check the Optional value is nil or not you can use  `isNil` or `isNotNil` to check that. 

```
 let value: Int?
 let result = value.unwrap
 let isNil = value.isNil // prints true
 print(result) // prints 0
 
 let value: String? = "Hello"
 let result = value.unwrap
 let isNil = value.isNil // prints false
 print(result) // prints Hello
