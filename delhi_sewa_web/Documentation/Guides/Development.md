# Development Guide

## Principles

- Inspect before modifying.
- Reuse before creating.
- Keep changes focused.
- Avoid redundant code.
- Avoid unnecessary dependencies.
- Keep security requirements explicit.
- Prefer simple solutions until complexity is justified.

## Workflow

Before changing code:

1. Read relevant documentation.
2. Inspect the existing implementation.
3. Search for reusable code.
4. Identify affected architectural boundaries.
5. Consider security implications.
6. Plan the smallest coherent change.

After changing code:

1. Run formatting.
2. Run linting.
3. Run type checking.
4. Run relevant tests.
5. Run the production build when appropriate.

## LLM-Assisted Development

Coding agents must inspect existing code and documentation before implementing changes.

Agents must not introduce duplicate abstractions, unnecessary dependencies, or architectural changes without justification.
