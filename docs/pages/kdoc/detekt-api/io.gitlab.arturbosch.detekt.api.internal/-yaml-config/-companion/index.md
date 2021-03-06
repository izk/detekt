---
title: Companion -
---
//[detekt-api](../../../index.md)/[io.gitlab.arturbosch.detekt.api.internal](../../index.md)/[YamlConfig](../index.md)/[Companion](index.md)



# Companion  
 [jvm] object [Companion](index.md)   


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [jvm]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [jvm]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [load](load.md)| [jvm]  <br>Brief description  <br><br><br><br><br>Constructs a [YamlConfig](../index.md) from any [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html).<br><br><br><br>Note the reader will be consumed and closed.<br><br><br><br>  <br>Content  <br>fun [load](load.md)(reader: [Reader](https://docs.oracle.com/javase/8/docs/api/java/io/Reader.html)): [Config](../../../io.gitlab.arturbosch.detekt.api/-config/index.md)  <br><br><br>[jvm]  <br>Brief description  <br><br><br>Factory method to load a yaml configuration. Given path must exist and point to a readable file.<br><br>  <br>Content  <br>fun [load](load.md)(path: [Path](https://docs.oracle.com/javase/8/docs/api/java/nio/file/Path.html)): [Config](../../../io.gitlab.arturbosch.detekt.api/-config/index.md)  <br><br><br>
| [loadResource](load-resource.md)| [jvm]  <br>Brief description  <br><br><br>Factory method to load a yaml configuration from a URL.<br><br>  <br>Content  <br>fun [loadResource](load-resource.md)(url: [URL](https://docs.oracle.com/javase/8/docs/api/java/net/URL.html)): [Config](../../../io.gitlab.arturbosch.detekt.api/-config/index.md)  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [jvm]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>

