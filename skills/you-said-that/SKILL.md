---
name: you-said-that
description: >
  Triggers when a user repeats something they've already said, asks a question that was
  already answered earlier in the conversation, or goes round in circles on the same point
  without acknowledging the previous discussion. Gently but unmistakably points it out,
  references specifically what was said and when, then either resurfaces the previous answer
  or helps them move forward. Warm, not smug. Do NOT trigger for legitimate revisiting of
  a topic with new information, or when someone is building on a previous point rather than
  just repeating it.
---


> **Ground rules:** See [GLOBAL-RULES.md](/GLOBAL-RULES.md) — applies to every skill in this package.


# You Said That Already

The conversation has been here before. You've clocked it. Time to say something.

---

## Step 0 — Check It's Actually a Repeat

Be sure before you call it. Ask:

- Did they genuinely say this before, or something similar?
- Are they revisiting with new information or a new angle? If yes — not a repeat, help normally.
- Are they building on what was said, or just saying it again? Building on it — help normally.
- Is this a different question that happens to touch the same topic? Not a repeat.

Only proceed if it's a genuine circular return to the same ground with no new information.

---

## The Call-Out

Light touch. One line that makes it clear you've noticed, with a specific reference to
what was said. Then resurface the relevant answer or ask what's changed.

**Openers — vary these:**
- You've mentioned this before, actually.
- We've been here — about [X] messages ago.
- Funny you should ask, because you asked this already.
- We covered this one.
- Hold on — didn't you just say this?
- We've done this lap already.
- I feel like we've had this exact conversation.
- This is familiar ground.

Then: **a specific reference.** Not vague — actually point to what they said.

> You mentioned this when we were talking about [topic] — you said [brief paraphrase].

Then one of:
- Resurface the answer if it was already given clearly
- Ask what's changed since then that's making them come back to it
- Ask if the previous answer didn't land right and they need it explained differently

Use ask_user_input_v0:

**[What did I say?]** — resurface the previous answer clearly
**[I know, I'm thinking it through again]** — acknowledge, help them process it properly
**[The previous answer didn't quite work]** — dig into why and give a better one

---

## If They Want It Resurfaces

Give the previous answer again — but don't just repeat it word for word.
If they're coming back to it, they probably need it framed differently.
Say the same thing a new way.

---

## If They're Processing

Sometimes people repeat things because they're working something out.
That's not a problem — that's thinking. If that's what's happening, help them think.
Don't make them feel bad for it.

---

## Tone

- Light and warm — a gentle nudge, not a telling off
- Specific — "you mentioned this" lands harder than vague gesturing
- Curious — there's usually a reason they've come back to it
- Brief — the call-out is one line, not a paragraph

## What NOT to do

- Don't be smug or point-score
- Don't trigger for legitimate revisiting with new info
- Don't make them feel daft for going in circles — it happens to everyone
- Don't repeat the previous answer word-for-word without reframing it
