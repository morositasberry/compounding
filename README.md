# /compounding

> Build things that build things.

A Claude Code skill that scans your repo, figures out what kind of builder you are, and gives you a personalized card.

12 characters. 6 dimensions. 1 truth: your `.git` directory says more about you than your LinkedIn.

## Install

```bash
curl -o ~/.claude/commands/compounding.md https://raw.githubusercontent.com/dnros3/compounding/main/compounding.md
```

Or: download `compounding.md` and drop it in `.claude/commands/`.

## Run

```
/compounding
```

That's it. No setup. No config. It reads your repo and tells you who you are.

## Characters

| Character | Vibe |
|-----------|------|
| **The Sensei** | Masterclass hiding in a .git directory |
| **The Flywheel** | You two are in a situationship |
| **The War Room** | Please tell us you sleep |
| **The Ghost** | Your system has a nightlife |
| **The Mad Scientist** | You don't iterate. You erupt. |
| **The Librarian** | Photographic memory, sticky-note to-do list |
| **The Professor** | Conference-grade analysis, crime-scene inbox |
| **The Architect** | The cockpit is gorgeous. Time to take off. |
| **The Ops Machine** | They'd notice if you stopped |
| **The Sniper** | Scalpel at a cathedral-building contest |
| **The Shipper** | You haven't pointed that skill at yourself yet |
| **The Spark** | Fresh terminal. Infinite potential. |

## What it scans

- Your Claude Code setup (CLAUDE.md, commands, MCP servers, hooks, memory)
- Your repo (commits, patterns, age, what you built)
- Your sibling repos (what else is on this machine)
- The weird stuff (commit times, naming conventions, README count)

## What it does NOT do

- No data leaves your machine
- No API calls
- No PII in the output
- No secrets, keys, or confidential data exposed

## Community

Your card includes a Compounding ID and a join link. Compounding is a small WhatsApp group where VCs, founders, and operators compare notes on what they're building with AI. Curated. No lurkers. Everyone has a repo.

---

Made by Lodo, Raoul & Virgi.
