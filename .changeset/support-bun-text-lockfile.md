---
"mattpocock-skills": patch
---

Recognise the text-based `bun.lock` (the Bun v1.2+ default) alongside the legacy binary `bun.lockb` when detecting the package manager in `setup-ts-deep-modules` and `setup-pre-commit`. Agents running either skill on a modern Bun project no longer fall back to npm because only `bun.lockb` was checked (#1088).
