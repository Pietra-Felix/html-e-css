# AGENTS.md

## Repository context
- This repository contains a collection of standalone HTML and CSS exercises under the folder [exercicios de html e css](exercicios%20de%20html%20e%20css).
- Most work here is editing static pages and simple stylesheets. There is no build step, package manager, or automated test suite.
- Prefer small, localized changes that preserve each exercise's existing structure and filenames.

## Working conventions
- Keep HTML semantic and simple. When editing an exercise page, preserve its current folder layout and relative links.
- If an exercise already uses a local stylesheet or image assets, follow that pattern instead of introducing frameworks or new tooling.
- When adding or renaming files, keep them close to the relevant exercise folder and update links accordingly.
- Verify changes by opening the affected HTML page in a browser and checking that the content and layout still make sense.

## Developer preferences and workflow rules
- Do not generate aggressive inline ghost text or multi-line completions while the user is typing raw tags, elements, or CSS properties.
- Prefer the editor's native IntelliSense, Emmet abbreviations, and standard snippet triggers over AI-generated code blocks.
- Only provide code suggestions when the user explicitly pauses, uses a shortcut, or requests help.
- Act as a passive, high-utility assistant. Avoid rewriting whole structures when a small, scoped change is sufficient.
- Do not automate file changes or refactoring without explicit confirmation.
