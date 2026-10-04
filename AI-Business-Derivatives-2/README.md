# AI Business Derivatives (StarNest)

Working repo for the StarNest 17-part venture portfolio: master context, handoffs, project folders, AI assets, and chat history from every Claude/Codex session.

## Start here
- `STAR NEST MASTER CONTEXT.md` – the master handoff document; defines what to work on
- `AI Workforce Assets/StarNest_Projects/AGENTS.md` – instructions for AI agents
- `AI Workforce Assets/StarNest_Projects/01-…17-…` – one folder per project (first sprint offer: `17-ai-training`)
- `AI Workforce Assets/StarNest_Projects/SHARED/` – API catalog and shared rules
- `chats/` – exported chat history (see below)

## Adding chats
Name files `YYYY-MM-DD_short-topic.<ext>` so they sort by date.

- **claude.ai:** Settings > Privacy > Export data. Put the `conversations.json` from the emailed zip in `chats/claude-ai/`.
- **Claude Code / Cowork:** transcripts are in `~/.claude/projects/`; copy the `.jsonl` files you want to `chats/claude-code/`.
- **Codex:** transcripts are in `~/.codex/sessions/`; copy the files you want to `chats/codex/`.

Chats can contain private business details. Keep this repo **private**.
