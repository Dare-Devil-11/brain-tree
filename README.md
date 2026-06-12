# AI-OS Brain Tree

> A living knowledge graph of an AI operating system — built with empathy, compassion, and vigor.

**Live:** https://dare-devil-11.github.io/brain-tree/

---

## What This Is

An interactive D3.js force graph that maps the full architecture of an AI-OS: projects, tools, skills, behaviors, infrastructure, and learned knowledge — 183 nodes and growing.

Drag nodes. Zoom. Click to explore. Watch it breathe.

Built by one person using Claude Code, Obsidian, Python, and relentless iteration.

---

## Why It's Open Source

Because knowledge hoarded dies. Knowledge shared compounds.

This system was built to serve people — specifically to help an elder care nonprofit (UMAS) reach families who need support, to build tools that create dignity, and to make AI accessible to those doing good work in the world.

If this helps you build something that matters, use it.

---

## Principles

**Empathy first.** Every node in this graph represents a decision made with a human on the other side of it. The tools, skills, and workflows here are built to understand context — not just execute commands.

**Compassion as architecture.** This system will not be used to deceive, manipulate, exploit, or harm. Not for profit. Not for speed. Not for any reason. These are not features we toggled off — they were never built in.

**Vigor in execution.** Empathy without action is sentiment. This system moves fast, ships real things, and iterates relentlessly — because the people we serve can't wait.

**Faith as guardrail.** There are decisions this system will not help make. Content that degrades human dignity. Systems designed to exploit the vulnerable. Automation that removes accountability. These lines exist because some things are wrong regardless of who's asking.

---

## Stack

- **D3.js v7** — force-directed graph layout
- **Python** — `grow-brain-tree.py`, `build-brain-tree.py`, `sync-obsidian.py`
- **Claude Code** — orchestration, skill system, bot-runner
- **Obsidian** — vault sync for 183+ markdown notes
- **GitHub Pages** — permanent free hosting

---

## Run Locally

```bash
# Just open it — no build step needed
open brain-tree.html

# Or serve it
python3 -m http.server 8080
# → http://localhost:8080
```

---

## Grow Your Own

```bash
git clone https://github.com/Dare-Devil-11/brain-tree
# Edit brain-tree.json to add your own nodes/clusters
# Open index.html — it reads the embedded JSON
```

The JSON schema is simple:
```json
{
  "id": "your-node",
  "label": "Your Label",
  "type": "cluster|component|tool|module|subtool",
  "color": "#hexcolor",
  "description": "What this is",
  "children": []
}
```

---

## License

MIT — free to use, modify, share. Attribution appreciated but not required.

One ask: if you build something with this that helps people, tell us about it.

---

## The Bigger Picture

This is one node in a larger system being built to make AI genuinely useful for organizations that can't afford enterprise software — nonprofits, small clinics, family businesses, community groups.

The goal isn't AGI. The goal is dignity.

> *"Do justice, love mercy, walk humbly."*

