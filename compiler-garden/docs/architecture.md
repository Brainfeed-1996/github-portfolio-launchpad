# Compiler Garden Architecture

## Overview

Compiler Garden is a language tooling project designed to demonstrate the full pipeline from source text to executable behavior. It focuses on clarity of intermediate representations, principled diagnostics, and room for optimization experiments.

## Pipeline

```text
source
  |
  v
lexer
  |
  v
parser
  |
  v
AST
  |
  v
semantic analysis
  |
  v
typed IR
  |
  +--> optimizer passes
  |
  v
backend or VM
```

## Components

### Lexer
Produces tokens with source spans and lexical diagnostics.

### Parser
Builds structured syntax trees with recoverable parsing errors where possible.

### AST layer
Represents user-facing program structure before deeper semantic refinement.

### Semantic analysis
Resolves names, scopes, types, control-flow validity, and language invariants.

### IR layer
Normalizes semantics into a form better suited for transformation and execution.

### Optimizer
Applies correctness-preserving simplifications and transformations.

### Backend or VM
Executes or lowers programs while preserving debuggability and diagnostics.

## Design priorities

- excellent diagnostics
- clean separation of front-end and execution concerns
- explicit source mapping across stages
- room for experimentation with language features and optimizations
