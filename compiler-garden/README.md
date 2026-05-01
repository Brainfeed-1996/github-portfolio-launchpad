# Compiler Garden

Language tooling and compiler architecture project for parsing, semantic analysis, IR design, optimization, diagnostics, and execution backends.

Compiler Garden is a prestige portfolio project designed to demonstrate serious engineering depth through the construction of a coherent language toolchain. It covers the path from source text to executable behavior while emphasizing clean abstractions, diagnostic quality, semantic rigor, and room for optimization experiments.

---

## Why this project matters

Compiler work compresses many difficult ideas into one system:

- parsing and syntax design
- AST modeling
- scoping and type analysis
- control-flow reasoning
- intermediate representations
- optimization correctness
- execution models and diagnostics

That combination makes compiler projects disproportionately valuable in selective hiring processes. They signal precision, systems thinking, abstraction ability, and technical maturity.

## What this project demonstrates

- language and tooling design
- algorithmic and structural rigor
- diagnostic and developer experience thinking
- intermediate representation design
- optimization pipeline design
- VM or backend execution modeling

## Core capabilities

- lexer with source spans
- parser and recoverable syntax diagnostics
- AST and semantic analysis pipeline
- typed IR
- optimization passes
- interpreter or bytecode VM
- source mapping and error reporting
- language playground or REPL potential

## Architecture at a glance

```text
source
  |
  v
lexer -> parser -> AST -> semantic analysis -> typed IR -> optimizer -> VM/backend
```

## Why it stands out in a portfolio

Few candidates build compiler-like systems well. This kind of project creates excellent interview material for language tooling, developer infrastructure, backend systems, and generalist high-bar engineering roles.

## Suggested stack

- Rust, OCaml, or C++ for the compiler core
- TypeScript for a playground or interactive visualizer

## Documentation

- `docs/architecture.md`
- `docs/roadmap.md`

## License

Apache-2.0
