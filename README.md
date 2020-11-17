Scala Macros
============

This repository is a collection of some useful resources on Scala Macros.

Getting started:
- [Use Cases - Macros, Scala Documentation][1]
- [Scala Macros][2]


1\. Contents
------------

### [essential-macros](essential-macros)
Companion material for the Underscore "Essential Scala Macros" course
as well as for the author's talk, "Macros for the Rest of Us", presented at ScalaDays 2014.

### [macrology201](macrology201)
Material from live coding session "Macrology 201" workshop at flatMap 2014.

### [scala-macros-examples](scala-macros-examples)
Simple examples of scala macros for the two-part blog post at bbartosz.com.


2\. Scala Documentation Links
-----------------------------

Reflection:
 - [Overview - Reflection, Scala Documentation][36]
 - [Environment, Universes, and Mirrors - Reflection, Scala Documentation][38]
 - [Symbols, Trees, and Types -  Reflection -  Scala Documentation][37]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Universe][34]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Mirrors][33]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Types][32]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Symbols][31]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Trees][30]
 - [Scala Reflection Library 2.12.12 - scala.reflect.api.Trees$Tree][35]

Quasiquotes:
 - [Introduction - Quasiquotes, Scala Documentation][26]
 - [Hygiene - Quasiquotes, Scala Documentation][27]
 - [Syntax summary - Quasiquotes, Scala Documentation][28]
 - [Expression details - Quasiquotes, Scala Documentation][29]


3\. AST Explorer
----------------

Online AST explorer for Scala and other languages: [https://astexplorer.net/](https://astexplorer.net/).
The Scala AST explorer is based on [Scala Meta](https://scalameta.org/) library, used to read, analyze, 
transform and generate Scala programs.


4\. Stackoverflow Questions
---------------------------

 - [“dynamically” creating case classes with macros][3]
 - [Scala macro annotation - case class with type parameters][4]
 - [Detect case class in scala macro][5]
 - [Use Scala macros to generate methods][6]
 - [Infer a type of a tree in a scala macro][7]
 - [Scala macros: Derive type signature from a ValDef][8]
 - [Proper way to pattern match the value of a TypeTree from a ValDef in Scala Macros?][9]
 - [how to get method body tree in scala macros][10]
 - [How to pattern match types in Scala macros?][11]
 - [Exploring expression tree within scala macro][12]
 - [String interpolation and macro: how to get the StringContext and expression locations][13]
 - [Collecting all identifers in scope][14]
 - [Is there an alternative to the deprecated enclosingClass method in Scala refelection library?][15]
 - [constructing or modifying scala.reflect.api.Position][16]
 - [How to run official reflection example][17]


5\. Youtube Videos
------------------

 - [Macros for Mortals - NE Scala 2016][21]
 - [Magic at compile time. Metaprogramming in Scala by Bartosz Bąbol @ Functional Conf 2016][22]
 - [Scala Macros: What Are They, How Do They Work, and Who Uses Them?][23]
 - [Adventures in Metaprogramming: Macros versus Shapeless by Dave Gurnell][24]
 - [Introduction to code generation with scalameta by Michael Pollmeier][25]


6\. Other Discussion
--------------------

 - [Current state of macros in Scala?][18]
 - [meta-ticket: Quasiquotes are no longer being improved #10755][19]
 - [Macros: the Plan for Scala 3][20]



[1]: https://docs.scala-lang.org/overviews/macros/usecases.html
[2]: http://scalamacros.org/

[3]: https://stackoverflow.com/questions/22850340/dynamically-creating-case-classes-with-macros
[4]: https://stackoverflow.com/questions/38212789/scala-macro-annotation-case-class-with-type-parameters
[5]: https://stackoverflow.com/questions/44633267/detect-case-class-in-scala-macro
[6]: https://stackoverflow.com/questions/33279472/use-scala-macros-to-generate-methods
[7]: https://stackoverflow.com/questions/17394389/infer-a-type-of-a-tree-in-a-scala-macro
[8]: https://stackoverflow.com/questions/39492064/scala-macros-derive-type-signature-from-a-valdef
[9]: https://stackoverflow.com/questions/23671379/proper-way-to-pattern-match-the-value-of-a-typetree-from-a-valdef-in-scala-macro
[10]: https://stackoverflow.com/questions/50678819/how-to-get-method-body-tree-in-scala-macros
[11]: https://stackoverflow.com/questions/48390066/how-to-pattern-match-types-in-scala-macros
[12]: https://stackoverflow.com/questions/53640045/exploring-expression-tree-within-scala-macro
[13]: https://stackoverflow.com/questions/15329027/string-interpolation-and-macro-how-to-get-the-stringcontext-and-expression-loca
[14]: https://stackoverflow.com/questions/21445108/collecting-all-identifers-in-scope
[15]: https://stackoverflow.com/questions/58289852/is-there-an-alternative-to-the-deprecated-enclosingclass-method-in-scala-refelec
[16]: https://stackoverflow.com/questions/20417654/constructing-or-modifying-scala-reflect-api-position
[17]: https://stackoverflow.com/questions/56642599/how-to-run-official-reflection-example

[18]: https://www.reddit.com/r/scala/comments/87advo/current_state_of_macros_in_scala/
[19]: https://github.com/scala/bug/issues/10755
[20]: https://www.scala-lang.org/blog/2018/04/30/in-a-nutshell.html

[21]: https://www.youtube.com/watch?v=JOkmLR4KVH4
[22]: https://www.youtube.com/watch?v=uWtEL1spHqc
[23]: https://www.youtube.com/watch?v=iZjedoeOL00
[24]: https://www.youtube.com/watch?v=FBg7K6LKdVg
[25]: https://www.youtube.com/watch?v=l88-ljjtLO0

[26]: https://docs.scala-lang.org/overviews/quasiquotes/intro.html
[27]: https://docs.scala-lang.org/overviews/quasiquotes/hygiene.html
[28]: https://docs.scala-lang.org/overviews/quasiquotes/syntax-summary.html
[29]: https://docs.scala-lang.org/overviews/quasiquotes/expression-details.html
[30]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Trees.html
[31]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Symbols.html
[32]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Types.html
[33]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Mirrors.html
[34]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Universe.html
[35]: https://www.scala-lang.org/api/2.12.12/scala-reflect/scala/reflect/api/Trees$Tree.html
[36]: https://docs.scala-lang.org/overviews/reflection/overview.html#compile-time-reflection
[37]: https://docs.scala-lang.org/overviews/reflection/symbols-trees-types.html
[38]: https://docs.scala-lang.org/overviews/reflection/environment-universes-mirrors.html