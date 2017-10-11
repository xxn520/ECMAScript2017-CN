# 介绍

Ecma 标准定义了 ECMAScript 2017 语言规范。这是 ECMAScript 语言规范的第八个版本。1997 第一个版本发布以来，ECMAScript 已经成长为世界上使用最为广泛的编程语言之一。它作为浏览器端脚本语言而广泛地被人知晓，但是在服务端和嵌入式应用领域也被广泛接受。

ECMAScript 基于一些开创性的技术，它们中最有名的就是网景的 JavaScript 和微软的 JScript。该语言由网景公司的 Brendan Eich 创造，并且首次出现在网景公司的 Navigator 2.0 浏览器中。网景公司随后发布的浏览器和微软 Internet Explorer 3.0 之后的浏览器，都用到了它。

ECMAScript 语言标准的编制始于 1996 年 11 月。Ecma 标准的第一个版本是在 1997 年 6 月的 Ecma 大会上通过的。

在快速通道下，该 Ecma 标准被提交给 ISO/IEC JTC 1 \(国际标准化组织/国际电工委员会的第一联合技术委员会\)，并在 1998 年 4 月被批准成为国际标准 ISO/IEC 16262。1998 年 6 月的 Ema 大会通过了 ECMA-262 标准的第二个版本，来与国际标准 ISO/IEC 16262 对齐。第一版和第二版之间的变化是社论性质的。

标准的第三个版本介绍了强大的正则表达式、更好的字符串处理、新的控制语句、try/catch 异常处理、更严谨的错误定义、数字输出的格式化和为语言未来发展预留的一些小改动。ECMAScript 标准的第三版在 1999 年 12 月的 Ecma 大会上通过，对应的国际标准 ISO/IEC 16262:2002 在 2002 年 6 月发布。

在第三版发布之后，ECMAScript 因与万维网关联而被广泛接受，它也成为了所有浏览器支持的一种编程语言。很多有意义的工作开展起来，来编制 ECMAScript 的第四个版本。然而，这些工作没有作为 ECMAScript 的第四版完成和发布，一些内容被包含进了第六版。

ECMAScript 的第五版（发布为 ECMA-262 5thedition\) 纸面化了很多事实上已经在浏览器形成共识的语言规范，并且增加了第三版发布以来出现的一些新功能的支持。这些特性包括访问器属性，反射创建以及对象检测、属性特性的程序控制、新增的数组操作函数、JSON 对象编码格式、以及提供增强的错误检测和程序安全的严格模式。第五版在 2009 年 12 月的 Ecma 大会上通过。

第五版通过快速通道提交给 ISO/IEC JTC 1，成为了国际标准 ISO/IEC 16262:2011。ECMAScript 5.1 版本并入了一些小的修正，内容与 ISO/IEC 16262:2011 保持一致，并在 2011 年 6 月的 Ecma 大会上通过。

第六版集中地发展开始于 2009 年，也就是第五版将要发布的时候。不过，在此之前进行了大量的实验性和语言增强设计工作，这可以追溯到 1999 年的第三版。就真正意义上来说，第六版的完成十五年努力的成果。这个版本的目标是为构建大型应用、创建库以及其他语言编译为 ECMAScript 提供更好的支持。The goals for this addition included providing better support for large applications, library creation, and for use of ECMAScript as a compilation target for other languages. Some of its major enhancements included modules, class declarations, lexical block scoping, iterators and generators, promises for asynchronous programming, destructuring patterns, and proper tail calls. The ECMAScript library of built-ins was expanded to support additional data abstractions including maps, sets, and arrays of binary numeric values as well as additional support for Unicode supplemental characters in strings and regular expressions. The built-ins were also made extensible via subclassing. The sixth edition provides the foundation for regular, incremental language and library enhancements. The sixth edition was adopted by the General Assembly of June 2015.

ECMAScript 2016 was the first ECMAScript edition released under Ecma TC39's new yearly release cadence and open development process. A plain-text source document was built from the ECMAScript 2015 source document to serve as the base for further development entirely on GitHub. Over the year of this standard's development, hundreds of pull requests and issues were filed representing thousands of bug fixes, editorial fixes and other improvements. Additionally, numerous software tools were developed to aid in this effort including Ecmarkup, Ecmarkdown, and Grammarkdown. ES2016 also included support for a new exponentiation operator and adds a new method to Array.prototype called`includes`.

This specification introduces Async Functions, Shared Memory, and Atomics along with smaller language and library enhancements, bug fixes, and editorial updates. Async functions improve the asynchronous programming experience by providing syntax for promise-returning functions. Shared Memory and Atomics introduce a new[memory model](http://www.ecma-international.org/ecma-262/8.0/index.html#sec-memory-model)that allows multi-[agent](http://www.ecma-international.org/ecma-262/8.0/index.html#agent)programs to communicate using atomic operations that ensure a well-defined execution order even on parallel CPUs. This specification also includes new static methods on Object:`Object.values`,`Object.entries`, and`Object.getOwnPropertyDescriptors`.

Dozens of individuals representing many organizations have made very significant contributions within Ecma TC39 to the development of this edition and to the prior editions. In addition, a vibrant community has emerged supporting TC39's ECMAScript efforts. This community has reviewed numerous drafts, filed thousands of bug reports, performed implementation experiments, contributed test suites, and educated the world-wide developer community about ECMAScript. Unfortunately, it is impossible to identify and acknowledge every person and organization who has contributed to this effort.

Allen Wirfs-Brock  
ECMA-262, 6thEdition Project Editor

Brian Terlson  
ECMA-262, 7thEdition Project Editor

