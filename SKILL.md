---
name: gtp
description: Grill the product. Run when the user says "gtp" or /gtp, or asks to grill a product, game, mod, app, site or tool from the user's side. Ask the hard questions a would-be player, user or downloader would ask (why would I use, play, download or keep this?), answer them honestly from the actual product, then fix the problems and gaps that show up.
license: MIT
metadata:
  author: kevlar10x
  version: "1.0.0"
---

# GTP: grill the product

Look at the current product from the side of the person deciding whether to bother with it. The goal is to find every reason someone would scroll past, bounce, or uninstall, and then remove those reasons.

## 1. Know the product

Read what exists: code, files, mod page or store page, readme, screenshots, and what's been discussed. Work out who it's for and where they'd come across it (Nexus, GitHub, a store, a link someone shared).

## 2. Ask their questions

Ask what a real person asks, in the order they meet the product. Pick the 6 to 10 that matter most for this one:

- **Find:** Would I notice it? Do the title and thumbnail say what it is in two seconds?
- **Why:** What itch does it scratch? Why this over the alternatives, or over doing nothing (vanilla game, another mod, an app I already have)?
- **Trust:** Does it look safe and looked after? Real screenshots? Clear requirements, compatibility and version?
- **Try:** How long from download to the good part? Install steps, setup, first run, first minute.
- **Value:** What's the moment that makes it worth it, and is it obvious or buried?
- **Friction:** What breaks, confuses or annoys? Conflicts with other mods, saves or game updates? Does it uninstall cleanly?
- **Stay:** Why keep it, come back, or tell someone about it?

For games, also ask: is the first minute fun, is the goal clear, does the difficulty fit, is there a reason to play again?

## 3. Answer them yourself, honestly

Answer each from the real product, not from what it was meant to be. A weak answer, "not sure" or "no" marks a gap. Don't go easy on it: the user runs this to find problems before players do.

## 4. Fix the gaps

Fix everything that's safe to fix now: code, defaults, UX, mod page or readme copy, install steps, compatibility notes, screenshot plan. The usual rules still apply: humanizer for public writing, impeccable or anti-slop-art for visuals, publishing rules before anything goes public, and verify fixes before calling them done.

Gaps that need money, a public post, or a change to what the product fundamentally is: list them for the user instead of acting.

## 5. Report compactly

```
GTP: <product>
1. <question> → <honest answer> → fixed: <what>
2. <question> → <honest answer> → needs you: <why>
```

Then one line on what changed.
