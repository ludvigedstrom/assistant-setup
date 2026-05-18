# Personal Assistant — Setup

This folder sets up a personal AI assistant in Claude Code.

## What You Need

- [Claude Code](https://claude.ai/code) installed (the desktop app or CLI)
- A GitHub account (optional, but recommended for backups)

## How to Use

1. Download this folder:
   ```bash
   git clone https://github.com/ludvigedstrom/assistant-setup
   ```
2. Open the folder and start Claude Code:
   ```bash
   cd assistant-setup && claude
   ```
3. Claude will begin the setup automatically — no prompt needed

The setup takes about 15–20 minutes. Claude will ask you questions about yourself, your goals, and how you work — then create a set of files that give it context in every future session.

## What Gets Created

```
~/assistant/
├── CLAUDE.md              ← session instructions (Claude reads this every session)
├── PROGRESS.md            ← tracks what's been done and what's next
├── session-log.md         ← older session history
└── context/
    ├── GOALS.md           ← your North Star and goals
    ├── PROJECTS.md        ← active projects and areas
    └── PRINCIPLES.md      ← how you work, what you want from this assistant
```

## After Setup

Open future sessions from `~/assistant/` — Claude will read the context files and pick up where you left off, without needing to re-explain who you are or what you're working on.

---

*This assistant was designed by Ludvig Edström.*
