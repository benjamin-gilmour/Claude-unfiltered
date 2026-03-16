# ✂️ The Simplifier

Stops you mid-build to ask whether you actually need all of it.

---

## What it does

When you're visibly overcomplicating your approach — adding layers, tools, processes, or steps that the problem doesn't require — it stops you. Names what it's spotted. Proposes the simpler version and explains why it works.

Addresses the real reason people don't go simple: usually a worry that it won't scale, won't handle edge cases, or looks amateurish. Deals with those concerns directly. Then lets you decide — but you'll have to argue against simplicity, which is harder than it sounds.

The principle it enforces: you can always add complexity later when you genuinely need it. You can't always remove it.

---

## When it fires

**Fires when:**
- You're adding layers that the problem doesn't need
- You ask "am I overcomplicating this?" — because you usually are
- The approach is more complicated than the problem requires

**Does not fire when:**
- The complexity is genuinely serving the problem
- It's a specialist domain where this level of complexity is standard
- You have valid reasons for the approach that outweigh the simplicity argument

---

## Quick example

> **You:** I'm thinking of using a microservices architecture with separate auth, notifications, and data services, all talking over a message queue, with a Redis cache layer and a dedicated API gateway...
>
> **Claude:** Hang on. What are you actually trying to do here?
>
> If this is a side project or MVP with one developer and a few hundred users, you're describing infrastructure for a team of fifteen. A single Express app with a Postgres database will do everything you need and take a fraction of the time to build and debug.
>
> The complex version handles problems you don't have yet. The simple version handles the ones you do.
>
> **[Show me the simple version]** / **[There's a reason for the complexity]** / **[I know, I just like doing it this way]**

---

## Install

Download [SKILL.md](./SKILL.md) and upload it at **claude.ai → Settings → Skills**.

Or grab the full pack: [unfiltered-full.skill](../../packs/unfiltered-full.skill) includes all thirteen skills.
