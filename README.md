# DTC Static Ad Engine

A **Claude Code skill** for producing high-converting DTC static ad creatives end-to-end. Distilled from a real client cycle ,  the rules are scar tissue from things that failed.

- **Part 1 ,  Headlines:** Schwartz awareness × sophistication × LF8 desire × avatar × formula matrix. Hundreds of headlines, not one reworded.
- **Part 2 ,  Static visuals:** 110-concept library + visual matrix + hard design rules (catchy, pattern-interrupting; photos off by default).
- **Part 3 ,  Variations:** diagnose the ONE winner element (usually the visual), lock it, and interpolate concepts around it ,  Andromeda-ready (a distinct Entity ID per variation), never re-guessing the win.

Worked example throughout = **Eterna Drop** (botox-alternative, women 50+). A `CONFIG` block at the top adapts it to **any** brand.

## Install (as a Claude Code skill)
Clone into your Claude Code skills folder:

```bash
git clone https://github.com/georgimarincheshki2-ux/dtc-static-ad-engine.git ~/.claude/skills/dtc-static-ad-engine
```

Claude Code auto-discovers it. Activate it in chat with phrases like:
`направи статични` · `дай концепции` · `make creatives` · `направи вариация` · `multiply this winner`.

## Get the latest (updates)
```bash
cd ~/.claude/skills/dtc-static-ad-engine && git pull
```

## Files
- `SKILL.md` ,  the engine (source of truth: headline engine, visual engine, variation engine, end-to-end workflow)
- `VISUAL-CONCEPT-LIBRARY.md` ,  the 110 visual concepts across 10 families
