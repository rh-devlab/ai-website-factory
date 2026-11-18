# Contributing to Open-Source AI Website Factory

First off, thank you for considering contributing to **Open-Source AI Website Factory**! Our mission is to keep this 50-Source / 15-Mega-File knowledge engine the highest-density, zero-hallucination AI development system available for free.

## Core Contribution Principles

To prevent context bloat and maintain 100% deterministic code generation inside Google NotebookLM, every contribution MUST obey these 4 strict rules:

1. **Zero-Bloat & High-Density Rule:**
   - Do NOT submit raw multi-thousand-line documentation dumps, academic essays, or historical web theory.
   - Every rule or code snippet must be concise, actionable, and production-ready.
2. **Strict Compliance with the Supreme Constitution (`File 15`):**
   - Zero `any` types in TypeScript examples (use `unknown` + Zod validation).
   - Zero `// TODO` or `// ... rest of code` placeholders.
   - Zero raw Unicode emojis used as UI icons (always use `lucide-react` or crisp inline SVGs).
   - Zero hardcoded secrets or insecure client-side price calculations.
3. **Preserve the 15 Mega-File Architecture:**
   - Do not create arbitrary new files outside the `knowledge-base/` (`01_` through `15_`) structure. Place improvements inside the exact Mega-File governing that domain.
4. **NotebookLM Verification Requirement:**
   - Before submitting a Pull Request, test your updated Mega-File inside Google NotebookLM with `15_MASTER_SYSTEM_PROMPT.txt` active to verify zero truncation and clean compilation.

## How to Submit a Contribution

1. **Fork & Clone:** Fork this repository to your GitHub account and create a clear feature branch (e.g., `feat/nextjs-caching-rules` or `fix/webhook-idempotency`).
2. **Edit Carefully:** Update the target `.txt` file inside `knowledge-base/` while keeping formatting clean and plain-text safe.
3. **Open a Pull Request:** Submit your PR with a clear title, a summary of what engineering problem your addition solves, and confirmation that you tested it in NotebookLM.

## Reporting Bugs or Rule Conflicts

If you encounter any generated code flaw, outdated framework API, or conflicting rule across the 15 Mega-Files, please open an **Issue** detailing:
- The exact prompt used (`BUILD:` or `AUDIT:`)
- Which Mega-File (`01`–`15`) caused the conflict
- The expected production behavior
