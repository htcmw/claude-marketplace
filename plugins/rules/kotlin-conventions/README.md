# kotlin-conventions

Kotlin coding conventions for Claude Code projects.

## Rules

- **ktlint standard style** — follows the official Kotlin style guide
- **Naming**: `camelCase` for functions, `PascalCase` for classes
- **Immutability first**: prefer `val` over `var`, immutable collections over mutable
- **Nullability**: minimize nullable types, never use `!!`

## Auto-loading

This rule activates automatically when working with `*.kt` or `*.kts` files.

## Usage

Copy `rules/kotlin.md` to your project's `.claude/rules/` directory, or use it as a reference when writing project-specific rules.
