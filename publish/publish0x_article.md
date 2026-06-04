# git-context: The $2 Tool That Saves You 5 Minutes Every AI Coding Session

Every developer using AI coding assistants (GitHub Copilot, Codex, Claude, Cursor) knows the pain: you need to give the AI context about your codebase, and every time it's the same manual work — copy file trees, grep for important files, paste recent commits.

I got tired of it, so I built **git-context**.

## What it does

One command gives you a complete AI-ready context dump:

```
python3 git-context --files -o context.txt
```

Output includes:
- Project tree structure (respects .gitignore)
- Current branch, remote, and working tree status
- Recent commit history with graph
- All branch topology
- Source file contents with language-appropriate syntax highlighting

## Why it matters

AI coding assistants work BETTER with good context. But manually gathering that context takes 3–5 minutes every single time. If you use AI 5 times a day, that's 15–25 minutes wasted daily.

git-context costs $2. After 2 uses, it's paid for itself in time saved.

## Tech Details

- Pure Python 3, zero dependencies
- Respects .gitignore patterns by default
- Intelligent truncation at 15KB of source files (configurable)
- Works on any repo, any platform

## Get it

```
pip install git-context
# or just download the single script — no dependencies!
```

[GitHub: promptpolish-ai/git-context](https://github.com/promptpolish-ai/git-context)
[Buy on Gumroad — $2](https://gumroad.com/l/git-context)

---

*Built by a dev who got tired of copy-pasting file trees into AI chats. If this saves you time, buy me a coffee.*

