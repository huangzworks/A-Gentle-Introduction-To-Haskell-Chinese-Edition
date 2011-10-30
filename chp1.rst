1.绪言
*******

注意，我们编写此教程的目的不是教导如何学习编程，甚至也不是教导如何学习函数式编程——它的本意是取代艰深的《Haskell Report》\ [1]_\ ，为那些有编程经验(最好是函数式语言编程经验)的读者提供一份学习Haskell的简明教程。

我们介绍语言特性的步骤一般是这样的：首先，提出设想(idea)，定义一些相关术语(term)，然后给出一些代码示例(example)，最后给出Report中相关细节的链接。

另外，我们也避免从一开始就介绍过多的语法概念，相反，我们以代码示例作驱动，渐进性地引入对新语法的讲解，每次用[](中括号)包裹，就像[这样]。

一方面，我们建议你在初次阅读本教程时先忽略Report中的相关细节；另一方面，我们建议你在读完本教程之后，接着阅读Haskell标准库中\ ``Prelude``\ 模块的源码，因为该模块中有很多有用的代码示例，既可以给你一个关于真实Haskell程序的直观印象，也可以加深你对标准库中预定义函数及类型的理解。

最后，\ `Haskell的官方网站 <http://www.haskell.org/>`_\ ，提供了Haskell语言及相关实现的详尽信息，别忘了常去看看。

.. rubric:: 脚注

.. [1] Simon Peyton Jones (editor). Report on the Programming Language Haskell 98, A Non-strict Purely Functional Language. Yale University, Department of Computer Science Tech Report YALEU/DCS/RR-1106, Feb 1999.
