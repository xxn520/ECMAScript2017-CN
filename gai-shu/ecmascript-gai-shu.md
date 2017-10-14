# ECMAScript 概述

The following is an informal overview of ECMAScript—not all parts of the language are described. This overview is not part of the standard proper.

ECMAScript is object-based: basic language and host facilities are provided by objects, and an ECMAScript program is a cluster of communicating objects. In ECMAScript, an_object_is a collection of zero or more_properties_each with_attributes_that determine how each property can be used—for example, when the Writable attribute for a property is set tofalse, any attempt by executed ECMAScript code to assign a different value to the property fails. Properties are containers that hold other objects,_primitive values_, or_functions_. A primitive value is a member of one of the following built-in types:**Undefined**,**Null**,**Boolean**,**Number**,**String**, and**Symbol;**an object is a member of the built-in type**Object**; and a function is a callable object. A function that is associated with an object via a property is called a_method_.

ECMAScript defines a collection of_built-in objects_that round out the definition of ECMAScript entities. These built-in objects include the[global object](http://www.ecma-international.org/ecma-262/8.0/index.html#global-object); objects that are fundamental to the runtime semantics of the language including`Object`,`Function`,`Boolean`,`Symbol`, and various`Error`objects; objects that represent and manipulate numeric values including`Math`,`Number`, and`Date`; the text processing objects`String`and`RegExp`; objects that are indexed collections of values including`Array`and nine different kinds of Typed Arrays whose elements all have a specific numeric data representation; keyed collections including`Map`and`Set`objects; objects supporting structured data including the`JSON`object,`ArrayBuffer`,`SharedArrayBuffer`, and`DataView`; objects supporting control abstractions including generator functions and`Promise`objects; and reflection objects including`Proxy`and`Reflect`.

ECMAScript also defines a set of built-in_operators_. ECMAScript operators include various unary operations, multiplicative operators, additive operators, bitwise shift operators, relational operators, equality operators, binary bitwise operators, binary logical operators, assignment operators, and the comma operator.

Large ECMAScript programs are supported by_modules_which allow a program to be divided into multiple sequences of statements and declarations. Each module explicitly identifies declarations it uses that need to be provided by other modules and which of its declarations are available for use by other modules.

ECMAScript syntax intentionally resembles Java syntax. ECMAScript syntax is relaxed to enable it to serve as an easy-to-use scripting language. For example, a variable is not required to have its type declared nor are types associated with properties, and defined functions are not required to have their declarations appear textually before calls to them.

  


