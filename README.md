# CJB Thread Builder

Turn any Due Dilly newsletter, archival piece, or episode transcript into a polished X thread draft — with built-in editing and export options.

Works in Claude Chat, ChatGPT, and Claude Code.

---

## How to Use It

### Option 1 — Claude Chat

1. Open [claude.ai](https://claude.ai) and start a new conversation
2. Open `SKILL.md` in this repo, click **Raw**, select all, and copy
3. Paste the skill into the conversation
4. Paste your source text directly below it (newsletter, article, or transcript)
5. Hit send — you'll get a numbered thread draft back

---

### Option 2 — ChatGPT

1. Open [chat.openai.com](https://chat.openai.com) and start a new conversation
2. Open `SKILL.md` in this repo, click **Raw**, select all, and copy
3. Paste the skill into the conversation
4. Paste your source text directly below it (newsletter, article, or transcript)
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
/cjb-threads /path/to/episode.vtt
```

---

## What You Can Feed It

| Source type | How to use it |
|---|---|
| Due Dilly newsletter | Paste the full issue or a specific section |
| Archival article or analysis | Paste the text |
| Episode transcript (`.vtt`) | Pass the file path (Claude Code) or paste the raw text |

**Newsletters and articles** are already distilled — the skill threads them directly.

**Transcripts** get an extra step: the skill finds the sharpest argument in the conversation first, confirms the angle with you, then writes the thread.

---

## Once You Have a Draft

**To edit:** reply with what you want changed.
- "Rewrite tweet 4"
- "Sharpen the hook"
- "Cut to 8 tweets"
- "Make tweet 6 more specific"

**Check `[verify]` flags** — these are facts from the source to confirm before posting.

**To export:** type one of these commands:

| Command | What it does |
|---|---|
| `export notes` | Clean titled block ready to paste into Apple Notes |
| `export doc` | Formatted for Google Docs with dividers between tweets |
| `export post` | One tweet at a time, ready to copy and post to X |

Every export includes an attribution line at the end pointing back to Due Dilly.

---

## Saving Your Threads

Use `export notes` and paste each finished draft into a new Apple Note. Name it by topic and date. That's your thread library — come back to it anytime, copy it back into Claude or ChatGPT to keep editing.

---

## Tips

- You don't need the whole newsletter — a single section or argument works just as well
- The more specific your source material, the sharper the thread
- If a draft isn't landing, give it a tighter angle: "focus only on the valuation section" or "make the hook about the tax structure"
- For transcripts, the skill will tell you the angle it found before writing — you can redirect it if something else stood out

---

Built on Due Dilly archival research. Powered by [Claude](https://claude.ai) / [ChatGPT](https://chat.openai.com).
