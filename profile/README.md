# Glen Programming Language

## About

**Glen** is a systems programming language built for writing fast, predictable, and maintainable software.

It prioritizes:

* explicit semantics
* minimal runtime overhead
* direct control over behavior
* efficient native code generation

---

## Ecosystem

* **`glenc`** — compiler
* **`halo`** — build system
* **`gest`** — REST API layer
* **`gltk4`** — GTK4 bindings *(in progress)*

---

## Example

```glen
module main;

fn main() {
    println("Hello, Glen");
}
```

---

## Getting Started

```bash
git clone https://github.com/glenlang/glen
cd glen
make
./build/glenc run samples/hello.gln
```

---

## Philosophy

Glen is designed to be:

* simple, but not simplistic
* low-level, but ergonomic
* predictable, not magical

---

## Status

Glen is under active development.

Expect rapid iteration, breaking changes, and ongoing improvements.

---

## License

Apache License 2.0

---

## Organization

This organization contains the Glen compiler, standard libraries, tooling, and ecosystem projects.
