# camshaft

Experimental infrastructure for large multiphysics packages: an event-driven
command interpreter with a user-facing DSL, a schema-driven columnar store for
user objects, a message-dispatch system, and a language-neutral API for
packages built on top of it.

The project is in its design phase. No code has been written yet.

## Layout

- `design/` — the design report, in LaTeX: the requirements, a survey of
  prior art, the architecture and the reasoning behind it, the policies for
  validation, testing and errors, and a prototype plan.

## Building the report

```sh
cd design
make            # requires latexmk, pdflatex and biber
```

The PDF is a build artifact and is not tracked.
