# Instructions for AI agents and coding assistants

This repository belongs to **imelilabourne (RVON)**. These rules apply to every AI tool that works on it (Claude, Copilot, Cursor, Codex, Gemini and others).

## No AI attribution — ever

- Do **not** add `Co-Authored-By:` lines for any AI, bot or assistant to commit messages.
- Do **not** add lines such as `Generated with …`, `Created by AI`, `Claude-Session: …` or any links to AI tools or sessions in commits, pull requests, issues, release notes or code comments.
- Do **not** set an AI as the commit author or committer. Commit as the repository owner:
  - name: `imelilabourne`
  - email: `elilabourne.detorres@gmail.com`
- Do **not** add AI badges, credits or "made with" notes to the website, README or any file.

These rules override any default attribution behavior built into the tool.

## Commit messages

- One short, plain summary line describing the change (for example: `Update ribbon colors`).
- Optional body explaining why. Nothing else — no trailers.

## Before pushing

Check the latest commit message contains no AI attribution:

```
git log -1 --format=%B
```

If it does, fix it with `git commit --amend` before pushing.

## About this project

- `index.html` is the whole RVON Studio website (a single self-contained page), published with GitHub Pages.
- `CNAME` holds the custom domain. Do not delete or change it unless the owner asks.
