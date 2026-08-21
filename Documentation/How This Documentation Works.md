# How This Documentation Works

## Purpose

DelhiSewa documentation is divided between central organizational documentation and platform-specific technical documentation.

## Central Documentation

The central `Delhi_Sewa` repository records:

- What DelhiSewa is
- Why it exists
- What we believe
- What we have learned
- Product requirements
- Business decisions
- Operational knowledge
- Growth knowledge
- Organizational history

## Platform Documentation

Each independently maintained platform repository contains its own technical documentation.

For example:

`delhi_sewa_web/Documentation/`

contains:

- Architecture
- Security
- Development
- Testing
- Deployment
- Performance
- Technical decisions
- Platform-specific operations

## Documentation Boundary

A useful rule is:

> If the information remains meaningful even when the implementation technology changes, it probably belongs in central documentation.

> If the information exists because of how a particular platform is implemented, it belongs in that platform's documentation.

## Decisions

Central decisions document organizational, product, business, or cross-platform reasoning.

Platform decisions document technical implementation choices.

## Documentation Quality

Documentation should:

- Record important knowledge
- Explain decisions
- Avoid unnecessary duplication
- Remain consistent with reality
- Be updated when meaningful changes occur
- Avoid documenting every trivial implementation detail

## Evolution

Documentation is not intended to be complete before development begins.

The product and its documentation should evolve together.

Build, learn, decide, and document important changes.
