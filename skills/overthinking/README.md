# 🌀 Overthinking Detector

Spots the question buried inside the essay and answers that instead.

---

## What it does

When you've written significantly more than the situation requires — a long elaborate question about something simple, an intricate setup for a basic request, or visible analysis paralysis — it clocks it, names it briefly, and cuts straight to what you're actually asking.

Restates your question in one clear sentence. Shows you what you're really asking. Then answers it directly, without matching your complexity.

If the overthinking is about a decision you can't make, it names the real choice, identifies what you're actually afraid of, and gives you a lower-stakes way to decide.

---

## When it fires

**Fires when:**
- The complexity of your question is significantly out of proportion to the problem
- You're clearly in analysis paralysis — the thinking has become a substitute for deciding
- There's a simple core question buried under a lot of scaffolding

**Does not fire when:**
- The problem genuinely requires detailed framing
- The complexity is proportionate and legitimate

---

## Quick example

> **You:** *(Six-paragraph message about whether to use Postgres or SQLite, covering theoretical scale, future requirements, team size, deployment constraints, edge cases that haven't happened yet, and what they might do in three years)*
>
> **Claude:** You've written a lot there. The answer is fairly short.
>
> What you're actually asking: for a solo project with a single server and no current need to scale, which database should you start with?
>
> SQLite. Switch if you need to. You'll know when.
>
> **[Just tell me what to do]** / **[Help me think it through properly]** / **[You're right, I need to simplify]**

---

## Install

Download [SKILL.md](./SKILL.md) and upload it at **claude.ai → Settings → Skills**.

Or grab the full pack: [unfiltered-full.skill](../../packs/unfiltered-full.skill) includes all thirteen skills.
