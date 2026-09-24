# Compilers and Interpreters

Standalone learning repo. Work here on its own — no other repos required.

**Phase (for your own roadmap):** Foundations

## Context

Languages are not magic: source becomes tokens, AST, bytecode or machine code, then runs under a GC or allocator. Understanding that pipeline makes debugging, performance, and "how does V8 work?" much less mysterious. Self-contained here.

This repository is the single place for everything related to **Compilers and Interpreters**: notes, exercises, and small projects. Clone it, open it, and treat it as a complete unit of study.

## Scope

- Lexing and parsing
- Abstract syntax trees (ASTs)
- Bytecode and VMs vs ahead-of-time compilation
- Garbage collection basics
- How JS engines (e.g. V8-style pipelines) roughly work
- Interpreters vs compilers in practice

## Outcomes

When you are done with this repo, you should be able to:

- Sketch the pipeline from source text to execution
- Explain AST / bytecode / GC at a whiteboard level
- Build a tiny lexer or interpreter as a project in this repo

## How to work in this repo

1. Read / write concept notes under `notes/`.
2. Solve practice problems under `exercises/`.
3. Ship at least one small project under `projects/` that forces the ideas to stick.
4. Tick the checklist below as you go.

You do not need any other curriculum repo open while you work here.

## Layout

```
compilers-and-interpreters/
├── README.md       # Context and checklist (this file)
├── notes/          # Concept write-ups
├── exercises/      # Practice problems and solutions
└── projects/       # Mini builds that apply the topic
```

## Progress

- [ ] Core concepts noted
- [ ] Exercises completed
- [ ] Mini-project shipped
- [ ] Can explain the main ideas without looking anything up

## Resources

Add books, docs, courses, and articles here as you find them. Keep this list local to this topic.

---

_This repo is independent. Progress elsewhere does not block work here._
