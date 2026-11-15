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
- `whitepaper/` — a short white paper derived from the design report: the
  problem, the design in brief, what package developers and users write, and
  the plan and its risks.

## Building the documents

```sh
cd design        # or: cd whitepaper
make             # requires latexmk, pdflatex and biber
```

The PDFs are build artifacts and are not tracked.
