# Software Principles

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


## Table of Contents

- SOLID (object-oriented programming)
  - [Single Responsibility Principle](#single-responsibility-principle)
  - [Open–closed Principle](#open–closed-principle)
  - [Liskov substitution principle](#liskov-substitution-principle)
  - [Interface segregation principle](#interface-segregation-principle)
  - [Dependency inversion principle](#dependency-inversion-principle)


## Single Responsibility Principle

The [single responsibility principle](//en.wikipedia.org/wiki/Single_responsibility_principle)
is a computer programming principle that states that every module or class
should have responsibility over a single part of the functionality provided by
the software, and that responsibility should be entirely encapsulated by the
class. All its services should be narrowly aligned with that responsibility.
Robert C. Martin expresses the principle as,"A class should have only one reason
to change."


## Open–closed Principle

In object-oriented programming, the [open/closed principle](//en.wikipedia.org/wiki/Open–closed_principle)
states "software entities (classes, modules, functions, etc.) should be open
for extension, but closed for modification"; that is, such an entity can
allow its behaviour to be extended without modifying its source code.


## Liskov substitution principle

Substitutability is a principle in object-oriented programming stating that,
in a computer program, if S is a subtype of T, then objects of type T may be
replaced with objects of type S (i.e. an object of type T may be substituted
with any object of a subtype S) without altering any of the desirable properties
of the program (correctness, task performed, etc.). More formally, the Liskov
substitution principle (LSP) is a particular definition of a subtyping relation,
called (strong) behavioral subtyping, that was initially introduced by
Barbara Liskov in a 1987 conference keynote address titled Data abstraction
and hierarchy. It is a semantic rather than merely syntactic relation, because
it intends to guarantee semantic interoperability of types in a hierarchy,
object types in particular.


## Interface segregation principle

The interface-segregation principle (ISP) states that no client should be forced
to depend on methods it does not use.
ISP splits interfaces that are very large into smaller and more specific ones
so that clients will only have to know about the methods that are of interest
to them. Such shrunken interfaces are also called role interfaces.
ISP is intended to keep a system decoupled and thus easier to refactor, change,
and redeploy. ISP is one of the five SOLID principles of object-oriented design,
similar to the High Cohesion Principle of GRASP.


## Dependency inversion principle

In object-oriented design, the dependency inversion principle refers to a
specific form of decoupling software modules.
When following this principle, the conventional dependency relationships
established from high-level, policy-setting modules to low-level, dependency
modules are reversed, thus rendering high-level modules independent of the
low-level module implementation details. The principle states:

1. High-level modules should not depend on low-level modules. Both should depend on abstractions.
2. Abstractions should not depend on details. Details should depend on abstractions.
