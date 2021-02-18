# The Rust Book Notes

This is me following along with a book club. 
We are working through [The Rust Book](https://doc.rust-lang.org/stable/book/title-page.html)

Furthermore, for each 2 chapters we are trying to implement external projects.
Currently this repository includes:

**Chapters 1 + 2:**

### Bloomfilter.org: [Let's Implement a Bloom Filter](https://onatm.dev/2020/08/10/let-s-implement-a-bloom-filter/)

This project implements a Bloom Filter from scratch. A bloom filter is an efficient probabilistic data structure that has only two operations:
set membership and add

The bloom filter doesn't store any actual elements, only the membership of them.

False positives are possible, but false negatives are not. 

**Chapters 3 + 4:**

### browser_engine.org: [Let's Build a Browser Engine!](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html)

This project was written by an engineer that worked on the servo team at firefox for a long time.
It builds a simple browser engine with the following modules:

html parser, css parser, style tree, layout tree, painter

Also worth reading this: [How Browsers Work: Behind the Scenes of Modern Web Browsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

**Chapters 5 + 6**

### parser_combinators.org [Learning Parser Combinators with Rust](https://bodil.lol/parser-combinators/)

This project shows how we can use closures to build effective parsers for working with xml

**Chapters 7 + 8**

### crispy.org [Risp (in (Rust) (Lisp))](https://stopa.io/post/222)

This is a workalong of Peter Norvig's "Creating a lisp interpreter in Python", except it is implemented in Rust.

It starts as mainly just a calculator, and more is added to it

**Chapters 9 + 10**

### irwa.org [Introduction to Rust Web Applications](https://erwabook.com/intro/index.html)

This book walks through creating a Rust based full stack application. It covers building a sqlite database using diesel to set up the Object Relational Model.
They also deal with database migrations, setting up a REST API, creating a database access layer with a command line tool, and then using webassembly for the front end.

