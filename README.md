# 100Hire Setup Task — AI Coding Tools Portfolio

This repository documents the first step of the 100Hire portfolio assignment:
setting up AI-powered coding tools and pushing work to GitHub.

---

## Tools Installed

- **Cursor IDE** — Downloaded and installed from [cursor.com](https://cursor.com/)
- **Git** — Used for version control and pushing to GitHub
- **VS Code** — Used as an alternative during troubleshooting (see Issues section)

---

## Steps Completed

1. Installed **Cursor IDE** from cursor.com
2. Created a **GitHub account** and set up a public repository
3. Opened the repository folder in Cursor
4. Investigated Claude and Codex integration in Cursor (see Issues section)
5. Created this README.md file
6. Committed and pushed to GitHub

---

## Issues Encountered & How I Solved Them

### Issue 1: "Claude Code" extension not found in Cursor

**What the assignment said:**

> Add the Claude Code add-on in Cursor (Extensions → search "Claude Code")

**What I found:**
Searching "Claude Code", "claude", and "anthropic" in Cursor's Marketplace returned **No Result**.

**What I discovered:**
After researching, I found that Claude is not a Cursor marketplace extension.
It is built directly into Cursor as an **AI model**, accessible under:
`Settings → Models → Sonnet 4.6 / Opus 4.7`

Both **Claude Sonnet 4.6** and **Claude Opus 4.7** were already listed and enabled (green toggle) in the Models settings.

**Reference:** [cursor.com/blog/codex-model-harness](https://cursor.com/blog/codex-model-harness)

---

### Issue 2: "Codex" extension not found in Cursor Marketplace

**What the assignment said:**

> Add the Codex add-on in Cursor (Extensions → search "Codex")

**What I found:**
Searching "codex" and "openai" in Cursor's Marketplace returned **No Result**.

**What I discovered:**
Codex is also not a marketplace extension. It is a built-in model in Cursor, available under:
`Settings → Models → Codex 5.3`

**Codex 5.3** was listed and enabled in the Models settings.

---

### Alternative Approach: VS Code (with Cursor + Claude + Codex)

Since the assignment mentioned "extensions" which is standard VS Code terminology  
I also explored VS Code as an alternative setup:

- **Cursor** has a VS Code extension, meaning you can bring Cursor's AI capabilities
directly into VS Code
- **Claude Code** is available as both a CLI tool and a VS Code extension via Anthropic
- **Codex** is accessible via OpenAI's API and integrates with VS Code environments

This means VS Code can run all three tools simultaneously Cursor, Claude, and Codex as actual installable extensions, which matches the assignment's original instructions more literally.

However, after discovering that Cursor IDE natively includes both Claude and Codex as built-in models (no separate extension install needed), I completed the task within Cursor IDE directly, which is the cleaner and more streamlined setup.

---

## Key Takeaway

The assignment said "Extensions → search Claude Code / Codex" — this language pointed toward VS Code, where these tools exist as real extensions. In Cursor IDE, the equivalent is **Settings → Models**, where Claude (Sonnet 4.6, Opus 4.7) and Codex 5.3 are built in natively.

Figuring this out required independent research which I believe is exactly what  
this assignment was designed to test.

---

## Tech Stack

- Cursor IDE (Free Plan)
- Git + GitHub
- Claude Sonnet 4.6 + Opus 4.7 (built-in via Cursor Models)
- Codex 5.3 (built-in via Cursor Models)
- VS Code (explored as alternative supports Cursor extension, Claude Code, and Codex)

