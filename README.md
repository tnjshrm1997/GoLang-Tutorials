# GoLang-Tutorials

# Overview

Before I start explaining and talking about GoLang. We should know why we are doing this and why this particularly this language? So, Why GoLang? I’ll highlight a few of its benefits and attach link of 2-3 articles, where you can go and dig a bit deep into this question why GoLang?

  1. GoLang is a system-level language. It directly runs on the underlying hardware. Usually, the programming languages like Java or Python runs on three-level architecture. 
Human Readable Code -> Byte Code (Understood by JVM)-> Binary Code (Understood by Processor)
It compiles the human-readable code and compiles it to byte code which can be understood by  JVM or it’s virtual machine which usually runs on the top of OS. The virtual machine will interpret the code to binaries code that can be understood by the processor. These languages also handle object allocation and garbage collection. Languages like C/C++ are based on two-level execution architecture. 
Human Readable Code -> Binaries (Understood)
It removes one step in the execution cycle which improves the system performance. But we need to free up and allocate variables in these languages. They do not handle object allocation and garbage collection. 	
GoLang brings up both of these functionalities together. It is a compiled language like C/C++. So, it’s performance is almost similar to C/C++ and it also uses garbage collection and removal of objects. 

  2. GoLang is for large, distributed and highly scalable servers. 

# Introduction

Now, let’s discuss about basic introduction to GoLang. Most of the things we can google about this language. So, I don’t have many things to write on its introduction. But I’d really want to write about the specialty of GoLang.
GoLang is a statically typed compiled language. 
Built-in garbage collector and memory safety. 
It has UTF-8 encoding by default. 
It has built-in concurrency model with the help of GoRoutines.


References: 
https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65
https://medium.com/@Sandra_Parker/why-golang-is-the-future-part-1-ed7dd4f419d
https://en.wikipedia.org/wiki/Distributed_computing
https://blog.golang.org/concurrency-is-not-parallelism

