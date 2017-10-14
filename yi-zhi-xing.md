# 一致性

符合 ECMAScript 标准的实现必须提供和支持本规范中描述的所有类型、值、对象、属性、函数和程序语法语义。

符合 ECMAScript 标准的实现必须保证源文本的解释必须符合最新版本的 Unicode 标准和 ISO/IEC 10646。

符合 ECMAScript 标准的实现提供一个应用程序编程接口，支持需要适应不同人类语言和国家所使用的语言和文化约定的程序，实现该接口必须符合最新的 ECMA-402 规范。

符合 ECMAScript 标准的实现可能会提供超出本规范描述的其他类型、值、对象、属性和功能。另外，符合 ECMAScript 的实现可以为本规范描的对象提供本规范中未描述的属性以及用于这些属性的值，来说明书中描述的对象。

A conforming implementation of ECMAScript may provide additional types, values, objects, properties, and functions beyond those described in this specification. In particular, a conforming implementation of ECMAScript may provide properties not described in this specification, and values for those properties, for objects that are described in this specification.

A conforming implementation of ECMAScript may support program and regular expression syntax not described in this specification. In particular, a conforming implementation of ECMAScript may support program syntax that makes use of the “future reserved words” listed in subclause[11.6.2.2](http://www.ecma-international.org/ecma-262/8.0/index.html#sec-future-reserved-words)of this specification.

A conforming implementation of ECMAScript must not implement any extension that is listed as a Forbidden Extension in subclause[16.2](http://www.ecma-international.org/ecma-262/8.0/index.html#sec-forbidden-extensions).

