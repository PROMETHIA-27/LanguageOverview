# Language Overview
A list and brief analysis of every language I can think of or find.

Not intended as a deep analysis or criticism- rather as a source of inspiration for language ideas, or a list of interesting things to look into for programming language nerds.

Feel free to suggest languages, tags, or interesting things I missed in issues!

## Mainstream

### C#: 
Tags: JIT, CLR, OOP, Functional, Imperative, Static, Dynamic, Reflection

Interesting features: 
- Reflection
- Runtime code compilation 
- Attributes as metadata
- Dynamically-typed subset, primarily static
- Garbage Collector
- `using` keyword for delaying cleanup until end of scope

### Java:
Tags: JIT, JVM, OOP, Imperative, Static, Reflection

Interesting features:
- ??? Likely a subset of C#'s interesting features. Probably not digging deeper.

### Groovy:
Tags: JIT, JVM, OOP, Imperative, Static, Reflection

Interesting features:
- Effectively an improved java?

### Scala:
Tags: JIT, JVM, Functional, Reflection

Interesting features:
- Needs investigation

### Kotlin
Tags: JIT, JVM, Functional, Reflection

Interesting features:
- Needs investigation

### Python
Tags: Interpreted, OOP, Functional, Imperative, Dynamic

Interesting features:
- Significant whitespace in place of traditional syntax separators
- Utilizing more functional programming patterns to simplify traditional code patterns
- "One way to do things" philosophy

### Ruby
Tags: Dynamic, OOP, Procedural

Interesting features:
- Additive class redefinition
- Modules as composable abstract classes

## Popular
### Rust
Tags: Static, Functional, Imperative, Strongly typed, AOT

Interesting features:
- Token stream substitution macros
- Borrow checker
- RAII
- Tagged unions
- Inline LLVM IR
- Explicit copiability (linear types?)

### Julia
Tags: JIT, Static, Dynamic, Gradual, Strongly typed, Imperative, Functional, OOP

Interesting features:
- Multiple dispatch
- First-class types

### Zig
Tags: AOT, Static, Strongly typed, Imperative, Compile-time

Interesting features:
- `@import` macro constructs a structure representing contents of import
- Dedicated error type syntax
- 16 bit and 128 bit floats
- First-class types, but only at compile time
- Dedicated testing syntax
- Dedicated operators for overflow behavior of arithmetic
- Built-in vector types
- All structs are anonymous
- Defer to end of scope
- Extensive compile-time operations

## Historical

### C
Tags: Weak typing, Imperative, Procedural, Static

Interesting features:
- Inline assembly
- Text substitution macros
- Specified ABI
- Conditional compilation tools

### Algol
Tags: Strong typing, Static, Imperative, Functional, Concurrent

Interesting features:
- Explicit local allocation
- Complex numbers as primitives
- Recursive type definition
- Expression-orientation
- n-Dimensional arrays and slicing
- Tagged unions
- Custom operators

## Weird
### Pawn
Tags: JIT, Untyped, Imperative, Procedural

Interesting features:
- Small, capable of embedding
- Aimed at non-expert programmers
- Semicolons optional, but required for multi-statement lines
- Deterministic
- State machines are a language construct

Notes:
  This is basically like C but with the jank stripped out. If it only had pointers- which it doesn't- I would say we should use this instead of C to teach beginners. Honestly might be a decent idea anyway.
