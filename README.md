# Klang

Klang is an experimental programming language project focused on readable syntax, practical tooling, and flexible execution backends.

## Quick Start

### If Klang is installed

```bash
klang run klang/examples/hello.kl
klang build klang/examples/factorial.kl -o factorial.exe
```

### Run directly from this repository

```bash
python klang/bin/klang.py run klang/examples/hello.kl
python klang/bin/klang.py parse klang/examples/simple_function.kl
python klang/bin/klang.py build klang/examples/factorial.kl -o factorial.exe
python klang/bin/klang.py ide
```

## Core Capabilities

- Indentation-based syntax
- Variables, arithmetic, loops, and conditionals
- Function definitions and calls
- CLI workflows for parse, run, and build
- VM and LLVM backend support

## Documentation

- Language and tooling guide: `klang/README.md`
- Web documentation view: `docs.html`
- Project website: `index.html`