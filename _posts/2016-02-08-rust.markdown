---
layout: post
title:  "Rust lang"
date:   2016-02-08 15:16:44 +0100
categories: rust
---

Rust is a new language developed by Mozilla, it looks pretty cool and it aim to be as fast as C,
actually it should be interoperable with it.

The language is modern, it has generics, pattern matching, type inference like some high level languages
(e.g. Scala, Haskell) and it combines this features to the control you can have with a low level language.

However the most important selling points of the language are the fact that it promises to do safe system programming and simplify concurrency, actually with the same "tool", the concept of [ownership](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html).

It's usages are more focus to cases where you need predictable performance (it doesn't have a garbage collector):
Mozilla is using it for writing its new web browser engine [Servo](https://github.com/servo/servo).
It should be good, then, to do embedded development and the project [zinc.rs](https://zinc.rs/) looks promising. Also [Tessel 2](https://tessel.io/) support the language out of the box.

For web programming it looks like it's still early days, according at this [website](http://arewewebyet.com/) even if either [iron](http://ironframework.io/) or [nickel](http://nickel.rs/) look exciting.

I will start soon writing some Rust, I'm pretty excited about it.
