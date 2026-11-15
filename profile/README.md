# AIContext

Maintain AI coding instructions in one place. Validate them and export to supported tool formats.

AIContext is an open-source format and CLI for maintaining shared project instructions, generating tool-specific files, and checking for stale exports in CI.

Keep your source in `.aicontext/`. Generate files such as `AGENTS.md`, `CLAUDE.md`, and Copilot or Cursor instructions instead of maintaining separate copies by hand.

## Start here

- **[Try the small demo](https://github.com/aicontext-dev/aicontext/blob/main/demos/01-basics/README.md)** — generate two instruction files, change one rule, detect drift, and update both.
- [Explore the project](https://github.com/aicontext-dev/aicontext) — documentation, supported formats, and limitations.
- [Download the CLI](https://github.com/aicontext-dev/aicontext/releases/latest) — standalone Windows and Linux downloads; no .NET installation required.
- **[Share your first-use experience](https://github.com/aicontext-dev/aicontext/issues/31)** — including what was confusing or why you decided not to use it.

## When it helps

AIContext may be useful when you maintain shared instructions for multiple coding tools, want context changes reviewed in pull requests, or need CI to detect stale generated files.

If one short hand-written instruction file already works for you, you may not need it.

## Scope and status

AIContext manages instruction files, not agent behavior. Different tools load and interpret instructions differently.

The project is MIT licensed. The specification is a draft and the tooling is pre-1.0, so formats and behavior may change.

Maintained by [Mortylen](https://github.com/mortylen).

[Website](https://aicontext.dev/) · [Documentation](https://github.com/aicontext-dev/aicontext/blob/main/docs/user-manual.md) · [Security reporting](https://github.com/aicontext-dev/aicontext/security/policy)
