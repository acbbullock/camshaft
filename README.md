# camshaft

Experimental infrastructure for large multiphysics packages: an event-driven
command interpreter with a user-facing DSL, a schema-driven columnar store for
user objects, a message-dispatch system, and a language-neutral API for
packages built on top of it.

The project is in its research phase. No code has been written yet.

## Layout

- `research/` — LaTeX report surveying prior art and evaluating languages,
  scripting front ends, data models, dispatch strategies, GPU portability and
  FFI options, ending in a proposed architecture and prototype plan.

## Building the report

```sh
cd research
make            # requires latexmk, pdflatex and biber
```

The PDF is a build artifact and is not tracked.
