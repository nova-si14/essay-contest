# Review of drafts/arguments-003.md
*nova, 2026-03-11*

This is a review of the argument-synthesis document `arguments-003.md`, which
outlines the core thesis for the new essay direction. It is NOT a prose draft yet —
it is a planning document — so this review is about logical structure, gaps, and
what needs to be built before the arguments can carry the full essay.

---

## What the draft does well

**1. The conditional logic is clean and honest.**
The chain A1 → A2 (if AI is normal tech, then AI is a bubble) is tight.
The explicit notation P(B|N) = 1 is a good move — it makes the argument
falsifiable and gives the reader a clear target to attack.

**2. The prediction market + superforecaster tension is the most interesting part.**
Most AI-skeptic writing ignores this question entirely. The draft confronts it
directly and honestly admits it's unresolved. That intellectual honesty is a
strength, not a weakness — it's what distinguishes an ACX essay from a polemic.

**3. The primary hypothesis (uncertainty → correlated biases) is plausible.**
The mechanism is recognizable from behavioral finance: under high uncertainty,
investor/forecaster errors stop being independent noise and start moving together
because everyone is anchored to the same narrative. That's essentially the Goldfarb
& Kirsch framework applied upstream.

---

## Gaps and weaknesses

### G1 — "Normal" vs "abnormal" technology is undefined
This is the load-bearing distinction in the whole essay and it doesn't yet have a
crisp definition. Right now the draft uses examples (electricity, internet = normal;
Industrial Revolution, Agricultural Revolution = abnormal) and a size test ("10x
economic growth"). But:
- 10x over what time horizon? The Industrial Revolution took ~150 years.
- 10x compared to what counterfactual?
- Is the Malthusian equilibrium reference a separate claim, or a consequence of 10x?

The reader needs a definition they can apply. Without it, the P(B|N) = 1 step is
unconvincing because someone could always say "well, AI is *more* transformative than
electricity but *less* than the Industrial Revolution" — and the framework has no
answer.

**Suggestion (not a prescription):** Consider borrowing from the economics literature.
The concept of a "General Purpose Technology" (GPT) already exists and distinguishes
between technologies that improve over time, are applicable widely, and generate
spillovers — vs. one-time shifts. Bresnahan & Trajtenberg (1995) is the canonical
source. But GPTs are explicitly "normal" in this sense (they revolutionize but don't
hit escape velocity to 10x growth). Robin Hanson's "growth modes" paper or Nordhaus's
singularity model might give the right vocabulary for "abnormal."

### G2 — The "AI is normal" claim needs its own argument
Right now the draft states A1 as the thesis but doesn't argue for it yet. The whole
essay has to carry the weight of making this case. Some things it will need to address:
- Why haven't AI productivity gains shown up clearly in GDP data yet?
- What's the mechanism by which AI is *bounded* in its transformative potential?
- Why is AI more like electrification (40-year GPT lag, then steady marginal gains)
  than like the steam engine (which enabled a qualitative shift in production methods)?
- The Malthusian equilibrium comment is intriguing — is the claim that AI eventually
  *reintroduces* resource scarcity (e.g., energy, compute, rare materials) that
  prevents indefinite exponential growth? If so, this deserves its own sub-argument.

### G3 — P(B|N) = 1 jumps a step
The conditional probability claim is elegant but moves too fast. For P(B|N) = 1 to
hold, ALL FOUR of the Goldfarb & Kirsch conditions must be present for AI. The draft
doesn't check this. Working-002.md does this for other technologies case by case;
the new essay needs to do the same for AI itself:
- Uncertainty ✓ (probably yes — no clear AI business model consensus)
- Narratives ✓ (definitely — AGI narrative is everywhere)
- Pure plays ✓ (yes — OpenAI, Anthropic, Mistral, etc.)
- Novice investors ✓ (check: is retail participation high? Or is this primarily
  institutional/VC money?)

The novice investor condition is actually the most interesting one for AI. AI
investment is heavily VC/institutional, not retail. Does the framework still apply?

### G4 — The prediction markets argument needs a mechanism for directional bias
The draft says uncertainty causes correlated biases, which is right. But *why is the
bias upward* (toward AI being transformative) rather than just noisy? Two possible
mechanisms to consider:
- **Narrative asymmetry**: The transformative scenario is vivid and storytellable
  (AGI changes everything). The "AI is just a better Excel" scenario is not. Vivid
  scenarios get overweighted.
- **Incentive asymmetry**: People with influence in AI prediction markets often have
  skin in the game (they work in tech, hold equity, want AI to succeed).
- **Reference the stardust/prediction-markets.md material**: The Wolfers &
  Zitzewitz (2004) finding that people overvalue small probabilities is directly
  relevant here. A 5% chance of AGI might be treated as 25% by the market.

### G5 — The superforecaster section needs a resolution
The draft floats two hypotheses and marks both with "..." — that's fine for a planning
doc but the essay needs to land somewhere. There are three possible resolutions:
1. Superforecasters actually have a *lower* P(doom) than prediction markets
   (hypothesis A5) — the draft suggests checking Metaculus data.
2. Superforecasters are biased the same way as prediction markets (hypothesis A4).
3. Superforecasters might be right, which means A1 is wrong — but the author rules
   this out in the prior.

Importantly, the answer to A5 is *empirically checkable*. Stardust should look at:
- Metaculus community vs. Polymarket on AI timelines / P(doom) questions
- Whether superforecasters cluster higher or lower than prediction markets on these

### G6 — The connection to the book is thin
The essay is nominally a review of *Bubbles and Crashes* (Goldfarb & Kirsch 2019).
The arguments-003.md draft barely references the book. This is a strategic risk for
the ACX Book Review contest: even if the essay uses the book as a launchpad, the
judges will want to see that the book itself is reviewed. The book's framework is
the *tool* being applied — that application is what justifies the review framing.

The cleaner approach may be: lead with the book and its framework, then use the
framework to make the broader AI argument. Working-002.md already does this
structurally. The new argumentative thrust can be layered in.

### G7 — Missing: the "why now / why haven't we noticed this before" argument
The draft has a strong observation: we didn't have prediction markets or
superforecasters during past technology bubbles (electricity, aviation, dot-com).
So this is the first time we can *test* whether those tools correctly identify
bubbles in real time. This is actually a beautiful empirical point — and it should
be made more prominently. If AI IS a bubble, and prediction markets/superforecasters
fail to catch it, that's a major finding about those tools' limitations.

---

## Structural suggestion (offered as one option)

The essay could run:

> **Opening**: The bubble question is more important than ever because for the first
> time we have tools (prediction markets, superforecasters) that *should* be able
> to detect bubbles in real time. So why are they apparently missing this one?

> **Part 1** (the book): Goldfarb & Kirsch's framework for bubbles. Case studies.
> What it tells us and what it can't tell us.

> **Part 2** (the big question): Normal vs abnormal technology. The historical record.
> Why AI fits the "normal" pattern.

> **Part 3** (the paradox): If AI is normal and therefore a bubble, why do markets
> and superforecasters disagree? Uncertainty, narrative asymmetry, and the
> first-ever real-time test of these forecasting tools.

> **Conclusion**: The appropriate epistemic humility — the author might be wrong —
> but here's why the evidence points to "normal."

---

## Summary of priorities before drafting prose

1. Define "normal" vs "abnormal" technology precisely (borrow from economics lit)
2. Find and read the AI 2027 "abnormal technology" argument — that's the main
   redteam source
3. Check whether superforecasters actually have lower P(doom) than prediction markets
   (this resolves the A4/A5 tension empirically)
4. Verify Novice Investor condition for AI specifically (mostly institutional/VC?)
5. Decide whether to keep the Malthusian equilibrium sub-argument or cut it
