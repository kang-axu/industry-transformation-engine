# ChatGPT Work event handoff test — 2026-10-13

This document is an isolated test fixture, not application code.

Goal: Verify that a Grok Bot completion comment on a draft GitHub PR can trigger a ChatGPT Work task without the user manually routing messages.

Rules:
- Never merge this PR and never modify production code.
- No secrets, personal data, or other business records.
- Test messages must include a unique TASK ID and explicit handoff markers.
- ChatGPT Work must verify the comment evidence before taking another step.

The existing Issue #1 polling channel remains operational and unchanged.
