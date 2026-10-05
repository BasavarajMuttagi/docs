# Documentation project instructions

## About this project

- This is the **React Interview & Core Architecture Guide** built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Grounded in official React documentation (`react.dev`), Nadia Makarevich's *Advanced React* (`reference.pdf`), and React 19 primitives
- Configured with Baseten visual styling (mint `#19e76e`, light `#f5f8f4`, dark `#0e0e0e`)

## Terminology

- Use "re-render" (hyphenated), not "rerender"
- Use "Fiber", "render phase", and "commit phase" precisely
- Use "updater function", not "functional state"
- Reference React 19 APIs (`useActionState`, `useOptimistic`, `use()`)

## Style preferences

- Lead every topic with the **30-Second Interview Pitch** `<Card icon="microphone">`
- Detail Fiber internals under **Under The Hood (Fiber Engine & Architecture)**
- Provide side-by-side `<CodeGroup>` comparisons for implementation patterns
- Highlight gotchas in **Pitfalls & Anti-Patterns** with `<Warning>` and `<CodeGroup>` (Buggy vs Senior Solution)
- Provide drillable interview questions in `<AccordionGroup>`
- Code formatting for file names, commands, paths, and code references
