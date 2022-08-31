---
title: Software Design document
aliases:
- Technical spec
- Software Architecture document
---

A Software Design Document or Architecture Document is a piece of [[Technical writing]] that defines a plan for solving a problem with software. It is necessary because software is so complex and requires so many decisions and trade-offs, it cannot be inferred from reading source code.

Should be written by project lead, for projects that take 1 engineer month or more.[^1]

## Examples of great documents

- [Audacity](http://aosabook.org/en/audacity.html)
- [Git](http://aosabook.org/en/git.html)
- [Rust-analyser](https://github.com/rust-lang/rust-analyzer/blob/d7c99931d05e3723d878bea5dc26766791fa4e69/docs/dev/architecture.md)
- [Selenium](http://aosabook.org/en/selenium.html)
- Stack Overflow, on [Nick Craver's blog](https://nickcraver.com/blog/2016/02/17/stack-overflow-the-architecture-2016-edition/). Beware, this was written *after* Stack Overflow was made, and architecture documents are generally written before a project starts. Thus, you should read additional documents.

More at [The Architecture of Open Source Applications](http://aosabook.org/en/index.html).

## Components of a design document

Future maintainers will want to read it. Thus it's worth placing it somewhere they can easily read it. One recommendation is to make a file called `ARCHITECTURE.md`. [^2]

Aleksey Kladov suggests mentioning significant files and modules, but not linking to them.

Invariants, or exclusions. If you have intentionally excluded something from the design, that thing should be defined along with the reason why. Future maintainers cannot know why something doesn't exist.[^3]

<!-- Eventually the section below should be removed -->

## Guides to writing architecture documents

The open source [arc42 document framework](https://docs.arc42.org/home/) is considered by many to be the best. Features many examples and is entirely free to use.

Free Code Camp has a guide: [How to write a good software design doc](https://www.freecodecamp.org/news/how-to-write-a-good-software-design-document-66fcf019569c/)

[^1]: "As a general rule of thumb, if you are working on a project that might take 1 engineer-month or more, you should write a design doc. But don’t stop there — a lot of smaller projects could benefit from a mini design doc too." [How to write a good software design doc](https://www.freecodecamp.org/news/how-to-write-a-good-software-design-document-66fcf019569c/)
[^2]: "If you maintain an open-source project in the range of 10k-200k lines of code, I strongly encourage you to add an `ARCHITECTURE` document next to `README` and `CONTRIBUTING`." [ARCHITECTURE.md](https://matklad.github.io//2021/02/06/ARCHITECTURE.md.html)
[^3]: "Explicitly call-out architectural invariants. Often, important invariants are expressed as an _absence_ of something, and it’s pretty hard to divine that from reading the code. Think about a common example from web development: nothing in the model layer specifically doesn’t depend on the views." [ARCHITECTURE.md](https://matklad.github.io//2021/02/06/ARCHITECTURE.md.html)