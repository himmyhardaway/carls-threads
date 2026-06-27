# CJB Thread Builder

Turn any Due Dilly newsletter or archival piece into a polished X thread draft — with built-in editing and export options.

Works in Claude Chat, ChatGPT, and Claude Code.

---

## How to Use It

### Option 1 — Claude Chat

1. Open [claude.ai](https://claude.ai) and start a new conversation
2. Open `SKILL.md` in this repo, click **Raw**, select all, and copy
3. Paste the skill into the conversation
4. Paste your Due Dilly source text directly below it
5. Hit send — you'll get a numbered thread draft back

---

### Option 2 — ChatGPT

1. Open [chat.openai.com](https://chat.openai.com) and start a new conversation
2. Open `SKILL.md` in this repo, click **Raw**, select all, and copy
3. Paste the skill into the conversation
4. Paste your Due Dilly source text directly below it
5. Hit send — you'll get a numbered thread draft back

---

### Option 3 — Claude Code

1. Copy `SKILL.md` into your Claude commands folder:
```bash
cp SKILL.md ~/.claude/commands/cjb-threads.md
```
2. Run it with a path to your source file:
```
/cjb-threads /path/to/newsletter.txt
```

---

## Once You Have a Draft

**To edit:** reply with what you want changed.
- "Rewrite tweet 4"
- "Sharpen the hook"
- "Cut to 8 tweets"
- "Make tweet 6 more specific"

**To export:** type one of these commands:

| Command | What it does |
|---|---|
| `export notes` | Clean block to paste into Apple Notes — includes title and date |
| `export doc` | Formatted for Google Docs with dividers between tweets |
| `export post` | One tweet at a time, ready to copy and post to X |

---

## Saving Your Threads

Use `export notes` and paste each finished draft into a new Apple Note named by topic. That's your thread library.

---

## Tips

- You don't need the whole newsletter — a single section or argument works
- The more specific your source material, the sharper the thread
- If a draft isn't landing, give it a tighter angle: "focus only on the valuation section" or "make the hook about the tax structure"

---

Built on Due Dilly archival research. Powered by [Claude](https://claude.ai) / [ChatGPT](https://chat.openai.com).
