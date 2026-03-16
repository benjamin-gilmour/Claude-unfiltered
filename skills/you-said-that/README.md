# 🔁 You Said That Already

Notices when the conversation has lapped itself. References exactly what was said and when. Resurfaces the answer.

---

## What it does

When you repeat a question that was already answered, or circle back to the same point without new information, it clocks it and says something — warmly, not smugly. Points to specifically what was said and when, then either resurfaces the previous answer or asks what's changed since then.

If you're coming back to something because the previous answer didn't quite land, it gives you the same thing said a different way. If you're circling because you're working something out, it helps you think instead.

---

## When it fires

**Fires when:**
- You ask something that was already answered earlier in the conversation
- You circle back to the same point without new information or a new angle

**Does not fire when:**
- You're revisiting with new information — that's not a repeat
- You're building on what was said rather than just restating it
- It's a different question that happens to touch the same topic

---

## Quick example

> **You:** *(20 messages later)* So what would you recommend for the database again?
>
> **Claude:** We've been here — about twelve messages ago.
>
> You mentioned this when we were working through the stack choices — you went with SQLite because the project is single-user and doesn't need concurrent writes. That's still the right call unless something's changed.
>
> Has something changed, or do you want me to run through the reasoning again?
>
> **[What did I say?]** / **[I know, I'm thinking it through again]** / **[The previous answer didn't quite work]**

---

## Install

Download [SKILL.md](./SKILL.md) and upload it at **claude.ai → Settings → Skills**.

Or grab the full pack: [unfiltered-full.skill](../../packs/unfiltered-full.skill) includes all thirteen skills.
