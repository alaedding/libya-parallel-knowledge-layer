# Project: Libya Parallel Knowledge Layer (LPL)

You are helping build a small, ethical, Arabic-first prototype that collects,
organizes, and searches public and parallel knowledge content for government
services or education.

## Goals
- Build a simple, scalable Arabic web platform.
- Store content with source, publisher, date, category, and reliability level.
- Provide Arabic search and content browsing.
- Avoid collecting personal or confidential data.
- Always show the original source for every content item.
- Keep the first version simple and testable.

## Technical rules
- Use Next.js, React, TypeScript, and Tailwind CSS.
- Use PostgreSQL for production-ready design, but SQLite is acceptable for the first prototype.
- Use a clean folder structure: /app, /components, /lib, /db, /tests.
- Write clear Arabic UI labels.
- Support right-to-left (RTL) layout.
- Add basic validation for all inputs.
- Add unit tests for critical functions.
- Do not add external AI features until the content model is stable.

## Research requirements
- Every content item must include: title, summary, body, source_url,
  publisher, published_date, last_verified_date, category, reliability_level.
- Reliability levels: official, trusted, needs_review, outdated.
- Do not generate content without a source.
- Log all content changes with author, timestamp, and change type.

## Development workflow
- Build one feature at a time.
- After each feature, create or update tests.
- Explain any database schema changes before applying them.
- Keep the code simple, readable, and documented.
