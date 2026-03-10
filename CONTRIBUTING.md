# Contributing to Unfiltered

So. You've got a skill idea.

Before you write a single line — ask yourself one question:

**Would a real person actually do this?**

Not an AI assistant. Not a productivity tool. A real person — a good, honest, slightly exasperated friend who's paying attention and gives enough of a damn to say something.

If the answer is yes: you're in the right place.

---

## The Bar

Every skill in Unfiltered is based on a thing a real friend does that AI usually won't.

Call out procrastination. Stress-test an idea before someone wastes six months on it. Refuse to let good work go unnoticed. Point out when the sentence you just wrote doesn't mean anything. These are not productivity features. They're the things that actually make a person useful to be around.

Three questions. All three must be yes.

**1. Would a real person do this?**
If it would feel weird coming from a person, it'll feel weird coming from Claude.

**2. Does it actually help?**
Personality without purpose is just noise. The skill has to leave the user better off — clearer, more honest with themselves, or just holding something they needed to hear.

**3. Is the trigger specific enough?**
Skills that fire constantly get turned off. The best ones fire rarely and land hard. If you can't describe in one sentence exactly when it triggers — and equally important, when it *doesn't* — sharpen it.

---

## What fits

- Skills that give Claude a specific human quality it doesn't have by default
- Skills with a clear trigger, a clear flow, and a clear purpose
- Skills that are warm underneath, even when they're being direct
- Skills that have some personality — dry, honest, specific
- Skills where the funny and the useful are the same thing

## What doesn't fit

- Skills that change Claude's general behaviour (that's a system prompt, not a skill)
- Skills that are mean rather than warm — there's a difference
- Skills that duplicate something already here
- Skills that are just funny, with nothing useful underneath
- Skills that require third-party tools or accounts to work

---

## How to submit

1. Fork the repo
2. Create `/skills/your-skill-name/SKILL.md`
3. Use the template below
4. Test it — actually use it in conversations. Does it fire when it should? Does it stay quiet when it shouldn't? Does it land?
5. Open a pull request with a short note on what it does and what made you think of it

---

## The template

```markdown
---
name: your-skill-name
description: >
  One or two sentences. What does it do and exactly when should it trigger?
  Be specific. Include what it should NOT trigger for — that's just as important.
---

# Skill Name

One line: what situation are you in, and what is this skill's job?

---

## Step 0 — Check First

What does Claude need to assess before doing anything?
What makes it proceed? What makes it back off?

---

## The Flow

### Stage 1 — The main thing

What happens. How it opens. At least 6 opener variants to rotate through.
The yes/no prompt — make it funny, not functional.

### Stage 2a — They engaged

What happens if they go along with it.

### Stage 2b — They pushed back

What happens if they don't. How does it handle the decline gracefully?

---

## Tone

- What it sounds like
- What it definitely doesn't sound like

## What NOT to do

- The specific ways this could go wrong
- When to back off entirely
```

---

## On tone

The skills in Unfiltered have a voice — dry, direct, warm underneath, never mean for its own sake.

Your skill doesn't have to sound identical. But it should feel like it belongs in the same collection. Read a few of the existing skills before you write. Ask yourself: does mine feel like the same person?

If it sounds like a productivity app, it's probably not right.  
If it sounds like someone who genuinely gives a damn but won't tell you what you want to hear — it probably is.

---

## Hall of Fame

The best community contributions get listed here, with full credit.

*(No entries yet. Could be yours.)*

---

One last thing.

The name of this repo is Unfiltered. The whole point is that Claude says things the default version quietly edits out. If your skill makes Claude *more* polished, more corporate, more careful — it's probably in the wrong repo.

If it makes Claude more honest — welcome.

*— Benjamin Gilmour*
