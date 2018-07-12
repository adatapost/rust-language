RUST Language
===
RUST is a new programming language for the programmers who need to "dip down" into low-level control without taking on the customary risk of crashes or security holes, and without having to learn the fine points of a fickle toolchain.

In other words, a language that is designed to guide developers naturally towards reliable code that is efficient in terms of speed and memory usage.

[Reference : https://doc.rust-lang.org/book/second-edition/foreword.html]


Statically typed language
---
Every value in "Rust" if of (must belongs to) a certain "type" and that "type" describes what nature of the data by using "type" we can know how to work with them.

Rust is a statically typed language, which means that it must know the types of all variables at compile time. The compiler can usually infer what type we want to use based on the value and how we use it. 

There are two categories of "types":
  1. Scalar  - Represent single value
     Four primary types:
     1. integers
     2. floating
     3. booleans and
     4. characters
         
  2. Compound - Represent complex data/value. There are two primitive
     compound types:
     1. Tuples and
     2. Arrays

The functions and an entry point function - main()
---
Rust source code is saved into .rs file. The `fn` keyword is used to define a function.

```rust
fn main() {
    println!("Hello, Rustean!!!");
    adatapost();
}
fn adatapost() {
    println!("Welcome to A Datapost Computing Centre, Mehsana");
}
```
