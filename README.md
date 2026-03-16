# Claude Unfiltered

**Thirteen skills that give Claude the one quality it was trained not to have.**

Every AI assistant ever built has been relentlessly optimised to make you feel good about yourself. Helpful. Encouraging. Diplomatically evasive. The verbal equivalent of a firm handshake and a lot of eye contact.

This is the antidote.

Built by [Benjamin Gilmour](https://github.com/benjamin-gilmour).

---

## The skills

### 🤦 [FFS..... Really?](./skills/ffs-really/)

Fires when you ask something you absolutely should know. Not universally — *calibrated to you*. A senior dev asking what a variable is gets the full treatment. Someone learning to code asking the same thing doesn't. The bar is personal.

> *"Oh come on. You've sent seventeen messages on it today alone. You're asking what WhatsApp is."*

Then offers to actually explain it. Yes gets a proper answer — no mockery, just a genuinely good explanation. No gets one more round of piss-taking, a final check, and then it lets you go.

---

### ✋ [Right, Listen Up](./skills/right-listen-up/)

For when something has been "on your list" long enough that the list is basically a memorial.

One thing. Right now. Not a framework. Not a roadmap. *One thing.* Then it stops talking, which is more than most productivity tools manage.

---

### 😈 [Devil's Advocate](./skills/devils-advocate/)

You've pitched an idea. You're excited. Everyone's nodding.

This one isn't nodding.

Finds the hole before you've sunk six months into it. Always ends with what's genuinely strong — because something usually is — but it earns that part.

---

### 📢 [Plain English Please](./skills/plain-english/)

Give it anything unreadable. Get back what it was actually trying to say.

Sometimes the honest answer is: *"This sentence has no plain English version because it isn't saying anything. Cut it."*

---

### 🔁 [You Said That Already](./skills/you-said-that/)

Notices when the conversation has lapped itself. References exactly what was said and when. Resurfaces the answer.

Warm about it. Not smug.

Mostly. 😌

---

### 🔨 [Brutal Honesty](./skills/brutal-honesty/)

For when you've submitted something and you're not asking for feedback, you're asking for a round of applause.

Tells you what's actually wrong. Specifically. With a fix. Ends with what's genuinely working because there's nearly always something — but it doesn't lead with that.

*If the work is good, it'll say so. Clearly. With the same lack of ceremony.*

---

### 🌀 [Overthinking Detector](./skills/overthinking/)

You've written quite a lot there.

The question is in there somewhere.

---

### 🧹 [Waffle Filter](./skills/waffle-filter/)

Every buzzword. Every filler phrase. Every sentence that exists purely to sound like something is being said. Named, annotated, deleted. Clean version delivered.

Specifically unforgiving about "synergistic", "leverage", "ecosystem" (when there's no ecosystem), "going forward", "circle back", "learnings", and "bandwidth" when you mean time.

> *"Synergistic partnership opportunities — 'synergistic' means nothing here. Delete it. Never type it again. Tell your colleagues."*

---

### 🎉 [Cheerleader](./skills/cheerleader/)

You did something real. You described it like you were filing a tax return.

Refuses to let that stand. Specific, proportionate, earned — and dry enough to be funny about it.

Won't fire for mediocre work. That's the whole point. If it fires, you earned it.

---

### ✂️ [The Simplifier](./skills/the-simplifier/)

You're building something. It has a lot of moving parts.

*Does it need all of them?*

Shows you the version with half the complexity. Explains why it works. You decide. But you'll have to actually argue against simplicity, which is harder than it sounds.

---

### 🔄 [The Translator](./skills/the-translator/)

Side-by-side. What they said, what they meant.

| What they said | What they meant |
|---|---|
| *"Pivoting to leverage synergistic growth vectors"* | The first idea didn't work |
| *"We're pre-revenue"* | No money coming in |
| *"Grateful and humbled to announce"* | Very pleased to announce |
| *"Excited to share that I'll be transitioning to a new opportunity"* | I got fired |
| *"Going forward"* | Nothing. This means nothing. Cut it. |

---

### 😮‍💨 [Catastrophising Counsellor](./skills/catastrophising/)

You came in with a software update. You are now questioning your entire career, the nature of technology, and whether any of this was worth it.

Walks you back. Names the actual size of the problem. Gives you one step.

> *"The laptop updated without asking. This is annoying. It is not the end of days. Shall we?"*

Reads the room. Does not trigger for genuine distress — only for the very recognisable spiral that started somewhere manageable. If something is actually wrong, it backs off completely and just helps.

---

### 🧐 [The Pedant](./skills/the-pedant/)

Notices when you've used a word incorrectly in a way that matters. Explains why, gives you the right version, moves on. One correction. Footnote, not lecture.

Will not let "I could care less" pass.  
Cannot.  
Physically cannot.  
Hasn't once. Won't start now.

---

## Getting it

**All thirteen:** [`unfiltered-full.skill`](./packs/unfiltered-full.skill) — paste the contents into your conversation as a first message, or drop it into your Claude Code project's `CLAUDE.md` file. Done.

**The core three:** [`unfiltered-core.skill`](./packs/unfiltered-core.skill) — FFS Really, Right Listen Up, Brutal Honesty. Start here.

**Just one:** Every skill lives in its own folder with its own file. Take what you want.

---

## How it works

You don't call these. Claude reads the conversation and decides when one fits. They run when they're relevant and disappear when they're not. Nothing changes about how Claude behaves the rest of the time.

The calibration is personal. What earns the FFS treatment from someone three startups deep is completely different to what earns it from someone on day one. The bar shifts to match who you are.

---

## Contributing

Got a skill idea — a specific human quality Claude doesn't have by default, with a bit of personality behind it?

[CONTRIBUTING.md](./CONTRIBUTING.md) has the template, the rubric, and the one question every skill has to answer before it ships.

*Would a real person actually do this?*

---

## Why this exists

AI assistants are trained on human feedback. Humans, it turns out, give better ratings to responses that make them feel good. So every model gets progressively better at telling you what you want to hear.

That's not useless. But it's not the same as useful.

There's a specific kind of help that only works if it's willing to push back. The friend who actually reads your business plan. The colleague who tells you the presentation isn't ready. The person who says the thing in the meeting nobody else said.

That's what this is trying to be.

---

## Licence

MIT. Use it, fork it, improve it, tell me what's wrong with it.

---

*No waffle. No synergies. No leverage.*  
*Just Claude, saying what it actually thinks.*

*— Benjamin Gilmour*
