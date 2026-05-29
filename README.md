<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
⚡ QUEST-DROP
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**What to do when bored — AI quest generator for real-life adventures, solo or with friends.**

No bars. No escape rooms. No "read a book."  
Just experiences you'll actually talk about.

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Quests](https://img.shields.io/badge/quests-growing-orange)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)

</div>

---

## What is this?

`quest-drop` is a Claude AI skill that generates **wildly unconventional side quests** on demand — for when you're bored, restless, or just done with the usual.

Chat with it. Get a quest. Do it. Tell no one. Or tell everyone.

Works solo or with friends. Day or night. Any city, any budget.

---

## How it works

Just open Claude and type any of:

```
quest
drop a quest
I'm bored
side quest
what should I do
```

You'll get something like:

```
━━━━━━━━━━━━━━━━━━━━━━━━━
⚡ QUEST DROPPED
━━━━━━━━━━━━━━━━━━━━━━━━━

🎭 THE ALTER EGO EXPERIMENT

You and your friends each invent a full alter ego — new name, job, 
tragic backstory, one weird obsession. Go somewhere public and live 
as them for 90 minutes. No breaking character. Debrief over food 
and decide which version of yourself you liked more.

🎯 Group  ⏱ 2–3 hrs  💸 Free  💀 Medium
🏆 XP: Unlocked a version of yourself you might actually miss

─ REROLL · HARDER · EASIER · SOLO · GROUP · MORE ─
```

---

## Commands

| Type this | Get this |
|---|---|
| `REROLL` | New quest, totally different energy |
| `HARDER` | More commitment, higher stakes |
| `EASIER` | Same spirit, lower friction |
| `SOLO` | Just for you |
| `GROUP 4` | For 4 people specifically |
| `NIGHT MODE` | Quests that only work after dark |
| `MORE` | Expand into a full quest arc |
| Any vibe/location | Context-aware quest |

---

## Quest Categories

| Category | What it feels like |
|---|---|
| 🧪 **SOCIAL ALCHEMY** | Unexpected human connection |
| 🏚 **URBAN ARCHAEOLOGY** | Hidden layers of your city |
| 💥 **CREATIVE DETONATION** | Make something absurd, now |
| 🪞 **PHILOSOPHICAL DARE** | Confront something real |
| 🌀 **SENSORY HIJACK** | Rewire your perception |
| 🎬 **CINEMATIC MISSION** | You're the main character |
| 🌪 **COLLECTIVE CHAOS** | Only works with 2+ people |
| ⏳ **TIME WARP** | Feels like another decade |

---

## Install the skill

1. Copy [`SKILL.md`](./SKILL.md) into your Claude skills folder
2. Start a new chat
3. Type `quest` and hit send

That's it.

---

## Add your own quests

Got a quest that belongs here? Open a PR and add it to [`quests.json`](./quests.json).

Rules:
- Must be unconventional (no bars, no escape rooms, no "learn a skill")
- Must be immediately doable — no planning, no booking
- Must be story-worthy — something you'd actually tell people about
- Bonus: slight friction — the "wait, should we actually do this?" feeling

```json
{
  "category": "SOCIAL ALCHEMY",
  "mode": "group",
  "difficulty": "medium",
  "time": "2-3 hrs",
  "cost": "free",
  "title": "THE ALTER EGO EXPERIMENT",
  "description": "Each person invents a full alter ego...",
  "xp": "Unlocked a version of yourself you might actually miss"
}
```

---

## Philosophy

Most "things to do" lists are written by people who have never been truly bored in an interesting way.

`quest-drop` is built on one idea: **the best experiences have a moment of "wait, should we actually do this?"** — that's the signal it's worth doing.

---

<div align="center">

Made for people who are bored of being bored.

**⚡ Drop a quest. Make a memory.**

</div>
