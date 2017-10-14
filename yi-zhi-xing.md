# 一致性

ECMAScript 的一致性实现必须提供和支持本规范中描述的所有类型、值、对象、属性、函数和程序语法语义。

ECMAScript 的一致性实现必须保证源文本的解释必须符合最新版本的 Unicode 标准和 ISO/IEC 10646。A conforming implementation of ECMAScript must interpret source text input in conformance with the latest version of the Unicode Standard and ISO/IEC 10646.

A conforming implementation of ECMAScript that provides an application programming interface that supports programs that need to adapt to the linguistic and cultural conventions used by different human languages and countries must implement the interface defined by the most recent edition of ECMA-402 that is compatible with this specification.

A conforming implementation of ECMAScript may provide additional types, values, objects, properties, and functions beyond those described in this specification. In particular, a conforming implementation of ECMAScript may provide properties not described in this specification, and values for those properties, for objects that are described in this specification.

A conforming implementation of ECMAScript may support program and regular expression syntax not described in this specification. In particular, a conforming implementation of ECMAScript may support program syntax that makes use of the “future reserved words” listed in subclause[11.6.2.2](http://www.ecma-international.org/ecma-262/8.0/index.html#sec-future-reserved-words)of this specification.

A conforming implementation of ECMAScript must not implement any extension that is listed as a Forbidden Extension in subclause[16.2](http://www.ecma-international.org/ecma-262/8.0/index.html#sec-forbidden-extensions).

