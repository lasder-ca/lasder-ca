# Writing guide

This guide defines the writing style used across the repositories and websites maintained by `lasder-ca`.

## Japanese

- Write the subject, action, and result so the relationship is clear on the first read.
- Use `は` to introduce a topic and `が` to identify a subject or new fact. Do not repeat either particle when two shorter sentences would be clearer.
- Connect sentences by meaning, not by adding conjunctions mechanically. Show the order of events when one action leads to another.
- Avoid a row of sentences ending in `〜します`. Mix complete sentences with concise descriptions, while keeping the grammar natural.
- Do not use vague metaphorical verbs such as `詰まる`, `刺さる`, or `回す` when a concrete verb is available.
- Avoid translated expressions and unnecessary English words. Keep technical terms in English only when that is the established name used in code or documentation.
- Prefer concrete descriptions over broad claims. State what the software does, when it does it, and what it does not guarantee.
- Do not start a product introduction with only `〜を開発しています`. First explain what the product is or what problem it addresses.
- Avoid promotional exaggeration, unsupported comparisons, and claims that cannot be verified from the repository.

## English

- Prefer direct sentences and concrete verbs.
- Introduce the problem before listing features.
- Keep headings descriptive rather than promotional.
- Separate current behavior, experimental behavior, and future plans.
- Do not claim safety, novelty, performance, or compatibility beyond the available evidence.

## Recommended structure

1. What the project is
2. The problem it addresses
3. How it works
4. Quick start
5. Supported features and current limits
6. Development and verification
7. Security and license

## Product introductions

A short introduction should answer these questions in order:

1. What is it?
2. What changes for the user or developer?
3. How does it work at a high level?
4. What is its current status?
5. Where can the reader inspect the source or documentation?

## Review checklist

- Is the main point clear from the first paragraph?
- Do the subject and predicate match?
- Are `は` and `が` doing distinct work?
- Are repeated sentence endings making the text mechanical?
- Can a vague expression be replaced with a concrete action?
- Are technical claims supported by code, tests, or documented evidence?
- Does the text distinguish released, experimental, and planned behavior?
- Are repository names, package names, versions, and links current?
