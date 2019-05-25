[![Build Status](https://travis-ci.org/sger/RustBooks.svg?branch=master)](https://travis-ci.org/sger/RustBooks)

# Rust Books

* [Books](#books)
  * [Starter Books](#starter-books)
  * [Advanced Books](#advanced-books)
* [Resources](#resources)

# Books

## Starter Books

### [The Rust Programming Language](https://doc.rust-lang.org/book/) *Free* or as [Print edition](https://www.nostarch.com/Rust)

<img src="https://www.nostarch.com/sites/default/files/styles/uc_product/public/RustProgrammingLanguage_cover_0.png" width="120px"/>

This book will teach you about the Rust Programming Language. Rust is a systems programming language focused on three goals: safety, speed, and concurrency. It maintains these goals without having a garbage collector, making it a useful language for a number of use cases other languages aren’t good at: embedding in other languages, programs with specific space and time requirements, and writing low-level code, like device drivers and operating systems. It improves on current languages targeting this space by having a number of compile-time safety checks that produce no runtime overhead, while eliminating all data races. Rust also aims to achieve ‘zero-cost abstractions’ even though some of these abstractions feel like those of a high-level language. Even then, Rust still allows precise control like a low-level language would.

### [The Rust Reference](https://doc.rust-lang.org/reference/) *Free*

This document is the primary reference for the Rust programming language. It provides three kinds of material:
* Chapters that informally describe each language construct and their use.
* Chapters that informally describe the memory model, concurrency model, runtime services, linkage model and debugging facilities.
* Appendix chapters providing rationale and references to languages that influenced the design.

### [Welcome to Rust-101](https://www.ralfj.de/projects/rust-101/main.html) *Free*

This is Rust-101, a small tutorial for the Rust language. It is intended to be an interactive, hands-on course: I believe the only way to really learn a language is to write code in it, so you should be coding during the course.
If you have any questions that are not answered here, check out the "Additional Resources" below. In particular, the IRC channel is filled with awesome people willing to help you! I spent lots of time there ;-)
I will assume some familiarity with programming, and hence not explain the basic concepts common to most languages. Instead, I will focus on what makes Rust special.

### [Rust by Example](http://rustbyexample.com/) *Free*

Rust by Example (RBE) is a collection of runnable examples that illustrate various Rust concepts and standard libraries. To get even more out of these examples, don't forget to [install Rust locally](http://www.rust-lang.org/install.html) and check out the [official docs](http://doc.rust-lang.org/std/). Additionally for the curious, you can also [check out the source code for this site](https://github.com/rust-lang/rust-by-example).

### [Rust Programming Step-by-Step](https://carlomilanesi.gitbooks.io/rust-programming-step-by-step/content/) *Free*

This book, that is still being written, allows a beginner programmer to learn how to program in the Rust programming language in a step-wise and easy way. Only a small knowledge of programming is required, preferably in C or C++ language. Let's say that to understand this text it is enough to know what is an integer and what a floating-point number, and to distinguish identifiers from strings literals.

### [A Gentle Introduction To Rust](https://github.com/stevedonovan/gentle-intro) *Free*

The aim of this tutorial is to take you to a place where you can read and write enough Rust to fully appreciate the excellent learning resources available online, in particular [The Book](https://doc.rust-lang.org/stable/book/). It's an opportunity to try before you buy, and get enough feeling for the power of the language to want to go deeper.

### [24 Days of Rust](https://zsiciarz.github.io/24daysofrust/) *Free*

Inspired by Ollie Charles and his excellent 24 days of Hackage series, this is an introduction to a number of Rust language features, useful libraries and cool projects built with Rust.

### [Learning Rust](https://dumindu.gitbooks.io/learning-rust/content/) *Free*

I am a Web Developer and just learning Rust. In here I tried to summarize what I learned and time to time I'll update this book. Hope this will be helpful for newcomers like me :)

### [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/README.html) *Free*

Note: this is a work in progress.

This book is an attempt to distil the Rust community's collective knowledge of Rust macros. 

### [Why Rust?](http://www.oreilly.com/programming/free/why-rust.csp)

<img src="http://covers.oreillystatic.com/images/0636920040446/cat.gif" width="120px"/>

While systems programming languages have greatly evolved since the introduction of C more than 40 years ago, our capacity for dumb mistakes with enormous consequences has remained unchanged, with vivid examples regularly in the news. This O'Reilly report examines Rust, a new systems programming language that combines safety and security with performance on a par with C and C++.

### [Learning Rust](https://www.packtpub.com/application-development/learning-rust)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b05114.png" width="120px"/>

Rust is a highly concurrent and high performance language that focuses on safety and speed, memory management, and writing clean code. It also guarantees thread safety, and its aim is to improve the performance of existing applications. It has been backed by Mozilla to solve the critical problem of concurrency.

### [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook)

<img src="https://images-na.ssl-images-amazon.com/images/I/41d88pwEATL._SX404_BO1,204,203,200_.jpg" width="120px"/>

This book comes with a lot of application-specific recipes to kick-start your development of real-world high-performance applications with the Rust programming language and integrating Rust units into your existing applications. In this book, you will find some 80 practical recipes written in Rust that will allow you to use the code samples right away in your existing applications. These recipes have been tested with stable rust compiler versions of 1.14.0 and above.

This book will help you understand the core concepts of the Rust language, enabling you to develop efficient and high-performance applications by incorporating features such as zero cost abstraction and better memory management.

We'll delve into advanced-level concepts such as error handling, macros, crates, and parallelism in Rust. Toward the end of the book, you will learn how to create HTTP servers and web services, building a strong foundational knowledge in server-side programming and enabling you to deliver solutions to build high-performance and safer production-level web applications and services using Rust.

### [Beginning Rust: From Novice to Professional](https://www.amazon.com/Beginning-Rust-Professional-Carlo-Milanesi/dp/1484234677)

<img src="https://images-na.ssl-images-amazon.com/images/I/41yxDbLMb4L._SX349_BO1,204,203,200_.jpg" width="120px"/>

*Beginning Rust* starts with the basics of Rust, including how to name objects, control execution flow, and handle primitive types. You’ll see how to do arithmetic, allocate memory, use iterators, and handle input/output. Once you have mastered these core skills, you’ll work on handling errors and using the object-oriented features of Rust to build robust Rust applications in no time.

### [Rust Programming By Example](https://www.packtpub.com/application-development/rust-programming-example)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b08821_cover.png" width="120px"/>

Beginning with an introduction to Rust, you'll learn the basic aspects such as its syntax, data types, functions, generics, control flows, and more. After this, you'll jump straight into building your first project, a Tetris game. Next you'll build a graphical music player and work with fast, reliable networking software using Tokio, the scalable and productive asynchronous IO Rust library.

Over the course of this book, you'll explore various features of Rust Programming including its SDL features, event loop, File I/O, and the famous GTK+ widget toolkit. Through these projects, you'll see how well Rust performs in terms of concurrency-including parallelism, reliability, improved performance, generics, macros, and thread safety. We'll also cover some asynchronous and reactive programming aspects of Rust.

### [Rust Standard Library Cookbook](https://www.packtpub.com/application-development/rust-standard-library-cookbook)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b09027.png" width="120px"/>

This book will take you through varied recipes to teach you how to leverage the Standard library to implement efficient solutions.

The book begins with a brief look at the basic modules of the Standard library and collections. From here, the recipes will cover packages that support file/directory handling and interaction through parsing. You will learn about packages related to advanced data structures, error handling, and networking. You will also learn to work with futures and experimental nightly features. The book also covers the most relevant external crates in Rust.

### [Rust Quick Start Guide](https://www.packtpub.com/application-development/rust-quick-start-guide)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/c/o/cover_18.png" width="120px"/>

Get familiar with writing programs in the trending new systems programming language that brings together the powerful performance of low-level languages with the advanced features like thread safety in multi-threaded code.

## Advanced Books

### [The Rustonomicon](https://doc.rust-lang.org/nightly/nomicon/) *Free*

This book digs into all the awful details that are necessary to understand in order to write correct Unsafe Rust programs. Due to the nature of this problem, it may lead to unleashing untold horrors that shatter your psyche into a billion infinitesimal fragments of despair.

Should you wish a long and happy career of writing Rust programs, you should turn back now and forget you ever saw this book. It is not necessary. However if you intend to write unsafe code -- or just want to dig into the guts of the language -- this book contains invaluable information.

### [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/5/7/5769os_rust20essentials.jpg" width="120px"/>

Starting by comparing Rust with other programming languages, this book will show you where and how to use Rust. It will discuss primitive types along with variables and their scope, binding and casting, simple functions, and ways to control execution flow in a program.

Next, the book covers flexible arrays, vectors, tuples, enums, and structs. You will then generalize the code with higher-order functions and generics applying it to closures, iterators, consumers, and so on. Memory safety is ensured by the compiler by using references, pointers, boxes, reference counting, and atomic reference counting. You will learn how to build macros and crates and discover concurrency for multicore execution.

By the end of this book, you will have successfully migrated to using Rust and will be able to use it as your main programming language.

### [Programming Rust](http://shop.oreilly.com/product/0636920040385.do)

<img src="https://covers.oreillystatic.com/images/0636920040385/lrg.jpg" width="120px"/>

This practical book introduces systems programmers to Rust, the new and cutting-edge language. You’ll learn how Rust offers the rare and valuable combination of statically verified memory safety and low-level control—imagine C++, but without dangling pointers, null pointer dereferences, leaks, or buffer overruns.

### [Mastering Rust](https://www.packtpub.com/application-development/mastering-rust)

<img src="https://images-na.ssl-images-amazon.com/images/I/51TGdQXiWDL._SX407_BO1,204,203,200_.jpg" width="120px"/>

If concurrent programs are giving you sleepless nights, Rust is your go-to language. Filled with real-world examples and explanations, this book will show you how you can build scalable and reliable programs for your organization.

We’ll teach you big level concepts that make Rust a great language. Improving performance, using generics, building macros, and working with threads are just some of the topics we’ll cover. We’ll talk about the official toolsets and ways to discover more. The book contains a mix of theory interspersed with hands-on tasks so you acquire the skills as well as the knowledge. Since programming cannot be learned by just reading, we provide exercises (and solutions) to hammer the concepts in.

### [Rust High Performance](https://www.packtpub.com/application-development/rust-high-performance)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b08822.png" width="120px"/>

At times, it is difficult to get the best performance out of Rust. This book teaches you to optimize the speed of your Rust code to the level of languages such as C/C++. You'll understand and fix common pitfalls, learn how to improve your productivity by using metaprogramming, and speed up your code by concurrently executing parts of it safely and easily. You will master the features of the language which will make you stand out and use them to really improve the efficiency of your algorithms

The book begins with a gentle introduction to help you identify bottlenecks when programming in Rust. We highlight common performance pitfalls, along with strategies to detect and resolve these issues early. We move on to mastering Rust's type system, which will enable us to create impressive optimizations in both performance and safety at compile time. You will then learn how to effectively manage memory in Rust, mastering the borrow checker. We move on to measuring performance and you will see how this affects the way you write code. Moving ahead, you will perform metaprogramming in Rust to boost the performance of your code and your productivity. You will finally learn parallel programming in Rust, which enables efficient and faster execution by using multithreading and asynchronous programming.

### [Rust in Action](https://www.manning.com/books/rust-in-action) 

<img src="https://images.manning.com/720/960/resize/book/4/099dd58-033f-4bec-b296-a82b49b20f3e/McNamara-Rust-MEAP-HI.png" width="120px"/>

Rust in Action introduces the Rust programming language by exploring numerous systems programming concepts and techniques.You'll be learning Rust by delving into how computers work under the hood. You'll find yourself playing with persistent storage, memory, networking and even tinkering with CPU instructions. The book takes you through using Rust to extend other applications and teaches you tricks to write blindingly fast code. You'll also discover parallel and concurrent programming. Filled to the brim with real-life use-cases and scenarios, you'll go beyond the Rust syntax and see what Rust has to offer in real-world use cases.

### [Network Programming with Rust](https://www.packtpub.com/application-development/network-programming-rust)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b09152_cover.png" width="120px">

Rust is low-level enough to provide fine-grained control over memory while providing safety through compile-time validation. This makes it uniquely suitable for writing low-level networking applications.

This book is divided into three main parts that will take you on an exciting journey of building a fully functional web server. The book starts with a solid introduction to Rust and essential networking concepts. This will lay a foundation for, and set the tone of, the entire book. In the second part, we will take an in-depth look at using Rust for networking software. From client-server networking using sockets to IPv4/v6, DNS, TCP, UDP, you will also learn about serializing and deserializing data using serde. The book shows how to communicate with REST servers over HTTP. The final part of the book discusses asynchronous network programming using the Tokio stack. Given the importance of security for modern systems, you will see how Rust supports common primitives such as TLS and public-key cryptography.

### [Hands-On Concurrency with Rust](https://www.packtpub.com/application-development/hands-concurrency-rust)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b08865_cover.png" width="120px"/>

This book will teach you to how to manage program performance on modern machines and build fast, memory-safe, and concurrent software in Rust. It starts with the fundamentals of Rust and discusses machine architecture concepts. You will be taken through ways to measure and improve the performance of Rust code systematically and how to write collections with confidence. You will learn about the Sync and Send traits applied to threads, and coordinate thread execution with locks, atomic primitives, data-parallelism, and more.

The book will show you how to efficiently embed Rust in C++ code and explore the functionalities of various crates for multithreaded applications. It explores implementations in depth. You will know how a mutex works and build several yourself. You will master radically different approaches that exist in the ecosystem for structuring and managing high-scale systems.

### [Hands-On Functional Programming in Rust](https://www.packtpub.com/application-development/hands-functional-programming-rust)

<img src="https://www.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b09736.png" width="120PX"/>

Functional Programming allows developers to divide programs into smaller, reusable components that ease the creation, testing, and maintenance of software as a whole. Combined with the power of Rust, you can develop robust and scalable applications that fulfill modern day software requirements. This book will help you discover all the Rust features that can be used to build software in a functional way.

We begin with a brief comparison of the functional and object-oriented approach to different problems and patterns. We then quickly look at the patterns of control flow, data the abstractions of these unique to Functional Programming. The next part covers how to create functional apps in Rust; mutability and ownership, which are exclusive to Rust, are also discussed. Pure functions are examined next and you'll master closures, their various types, and currying. We also look at implementing concurrency through functional design principles and metaprogramming using macros. Finally, we look at best practices for debugging and optimization.

By the end of the book, you will be familiar with the functional approach of programming and will be able to use these techniques on a daily basis.

### [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) *will be published in May 2019*

<img src="https://i.ibb.co/ccL8zzC/khrust.jpg" width="120px"/>

WebAssembly is more than just a revolutionary new technology. It’s reshaping how we build applications for the web and beyond. Where technologies like ActiveX and Flash have failed, you can now write code in whatever language you prefer and compile to WebAssembly for fast, type-safe code that runs in the browser, on mobile devices, embedded devices, and more. Combining WebAssembly’s portable, high-performance modules with Rust’s safety and power is a perfect development combination.

Learn how WebAssembly’s stack machine architecture works, install low-level wasm tools, and discover the dark art of writing raw wast code. Build on that foundation and learn how to compile WebAssembly modules from Rust by implementing the logic for a checkers game. Create wasm modules in Rust to interoperate with JavaScript in many compelling ways. Apply your new skills to the world of non-web hosts, and create everything from an app running on a Raspberry Pi that controls a lighting system, to a fully-functioning online multiplayer game engine where developers upload their own arena-bound WebAssembly combat modules.

Get started with WebAssembly today, and change the way you think about the web.

### [Step Ahead with Rust: Systems Programming in Rust](https://www.armstrong-publications.com/product/step-ahead-with-rust-super-combo/)

<img src="https://images-na.ssl-images-amazon.com/images/I/41ztdWA7yCL.jpg" width="120px"/>

From basic programming patterns to a peek under the hood of the language, Step Ahead with Rust aims to help you move from writing programs to building software in Rust. This book will show you the most important features of the Rust language, including cargo, type system, iterators and more. By the end of this book, you should be familiar with far more of them, and ready to tackle the rest of advanced topics. 

As you progress through the book, we recommend taking the time to experiment with what is presented in its pages. This book is all about the practical application of Rust, so applying it in practice is expected. The book covers: Cargo, Rust Type System, Iterators, Macros, Ownership, Borrowing and Lifetimes, Unsafe Patterns, Concurrency. A Step Ahead with Rust reader is expected to be a moderately experienced developer looking to improve their Rust development skills.

### [Hands-On Microservices with Rust 2018: How To Build Scalable and Reliable RESTful Microservices](https://www.amazon.co.uk/Hands-Microservices-Rust-2018-Scalable/dp/1789342759/ref=sr_1_6?s=books&ie=UTF8&qid=1545340800&sr=1-6&keywords=rust) *will be published in April 2019*

<img src="https://images-na.ssl-images-amazon.com/images/I/518eneKG4ML._SX260_.jpg" width="120px"/>

Microservice architecture is sweeping the world as the de facto pattern to build web-based applications. Rust is a language particularly well suited to building microservices. It is a new system programming language that offers a practical and safe alternative to C.

This book describes web development using the Rust programming language and will get you up and running with modern web frameworks and crates with examples of RESTful microservices creation. You will deep dive into Reactive programming, asynchronous programming and split our web application into a set of concurrent actors. The book provides several highly accurate HTTP-handling examples with manageable memory allocations. You will be walked through stateless high-performance microservices which are ideally suitable for computation or caching tasks and get to stateful microservices which are filled with persistent data and database interactions. As we move along, you will learn to use Rust macros to describe business or protocol entities of our application and compile them into native structs which will be performed at full speed with the help of the server's CPU.

Finally, you will be taken through examples of how to test and debug microservices and pack them to a tiny monolithic binary or put it into a container and deploy it to modern cloud platforms such as AWS.


# Resources

[**Learning Rust**](https://learning-rust.github.io/): Rust Programming Language Tutorials

[**Rust Playground**](https://play.rust-lang.org/): Run Rust in a browser

[**The Grammar**](https://doc.rust-lang.org/grammar.html): This document is the primary reference for the Rust programming language grammar

[**Rust Learning**](https://github.com/ctjhoa/rust-learning): longer list of Rust resourses

[**Rustlings**](https://github.com/carols10cents/rustlings): Small exercises to get you used to reading and writing Rust code. Includes practice reading and responding to compiler messages!

[**Rust Tutorials and Courses**](https://hackr.io/tutorials/learn-rust): Learn Rust from the best online Rust tutorials submitted and voted by the programming community.

[**Learn Rust with Examples**](https://github.com/rust-lang/rust-by-example): github site for *Rust by Example*

[**The Rust Programming Language**](https://www.youtube.com/watch?v=d1uraoHM8Gg): Hour-long YouTube video intro by Alex Crichton

[**RustConf 2016**](https://www.youtube.com/playlist?list=PLE7tQUdRKcybLShxegjn0xyTTDJeYwEkI): YouTube playlist of 9 talks from RustConf 2016

[**RustCamp 2015**](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t): YouTube playlist of 10 talks from RustCamp 2015

[**Are We Learning Yet?**](http://www.arewelearningyet.com/): List of resources for machine learning in Rust

[**Are We Web Yet?**](http://www.arewewebyet.org/): List of resources for web development in Rust

[**Rust Programming: Creating a Phoronix Reader Application**](https://mmstick.gitbooks.io/rust-programming-phoronix-reader-how-to/content/): step-by-step instructions regarding how to write a Phoronix Reader CLI application in Rust with colored output, but will evolve to also include a GTK3 GUI.

[**The Rusty Web**](https://davidmcneil.gitbooks.io/the-rusty-web/content/): This guide illustrates using the Rust programming language to target the web. The basic design pattern this project explores uses Rust to implement CPU bound portions of an app while using existing web technologies to handle user facing, I/O bound pieces.

# Contributing

Your contributions are always welcome, just follow [the rules](https://github.com/sger/RustBooks/blob/master/CONTRIBUTING.md)!

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
