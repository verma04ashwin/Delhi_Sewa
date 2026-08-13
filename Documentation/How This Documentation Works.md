# How This Documentation Works

## Purpose

This documentation system exists to preserve the institutional memory of DelhiSewa.

The goal is that future us should be able to understand:

- What we were trying to accomplish
- What we believed
- What we actually learned
- What we built
- Why we made important decisions
- What worked
- What failed
- What changed
- What we should do next

## Documentation vs Implementation

The central `Documentation/` directory contains product and organizational knowledge.

Implementation-specific technical details belong to their respective projects:

- `Website/`
- `Application/`
- `Backend/`
- `Admin/`
- `Infrastructure/`

For example:

> Why should DelhiSewa have a public website?

belongs in:

`Documentation/02 - Product/`

while:

> How is routing implemented in the website?

belongs in:

`Website/docs/`

## Evidence Chain

Important product development should ideally follow:

Assumption → Research → Experiment → Evidence → Decision → Implementation → Result → Learning

## Historical Principle

Do not rewrite old decisions simply because our thinking changed.

Instead:

1. Keep the original decision.
2. Record what changed.
3. Create a new decision if necessary.
4. Link the old and new decisions.

This preserves the history of how DelhiSewa evolved.

## Documentation Rule

If future us might ask:

> "Why did we do that?"

document it.
