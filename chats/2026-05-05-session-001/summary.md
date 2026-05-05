# Session 001 — 2026-05-05 — dwarkesh-ai-2026

## Context
First session on the `dwarkesh-ai-2026` branch. Contest: Dwarkesh Patel's $20K
blog prize, 1,000-word limit, May 10 deadline (5 days out). Stardust chose Q4
("what should countries not in the AI production chain do?") with TINA / FDI as
the working thesis, and added a "slight detour" engaging Q2 (when do AI labs
make money?) via the David Oks / Noah Smith airlines empty-core analogy.

## What was done

- **Initial review of `drafts/initial-001.md`.** Flagged: (1) Tolstoy epigraph
  was inverted/misattributed; (2) Scott Aaronson vs. Scott Alexander mix-up;
  (3) the draft pattern-matches exactly to the failure mode Dwarkesh called out
  in LLMs ("identifies 5 plausible answers, doesn't pick the crucial factor");
  (4) Q4 isn't actually answered with concrete actions; (5) citations thin;
  (6) word count drifting, Q2 detour pushes the draft over the 1,000-word limit
  (currently 1,279 → 2,822 by end of session, all per stardust's instruction
  not to cut yet).

- **Fixed Tolstoy quote** to canonical *Anna Karenina* opening; corrected
  "Karennina" → "Karenina". Commit `042890e`.

- **Fixed factual + typo issues in Q2 detour.** "XVII Century" → "XIX Century"
  (railroads), plus "reasons is", "Specially", "antropomorphize", "suceed",
  "an specific". Commit `f6a9b77`.

- **Drafted nova ideas under both "Maybe AI knows!" placeholders.** Commit
  `ee49aaa`:
  - **Q2:** switching costs accrue at the agent layer (memory, tool
    permissions, fine-tunes, audit logs), not the model. The airline analogy
    fails if labs build cloud-style switching costs above commoditized models.
    Real risk: regulators force agent-portability (Digital Markets Act for
    agents).
  - **Q4 (v1):** build power, not models. Park Chung-hee built KEPCO before
    Samsung; ERCOT explains Stargate. Concrete steps: Special Electricity
    Zones, one-stop hyperscaler permitting, FDI bound to local labor capture,
    skip the sovereign-model trap.

- **Stardust pushed back.** Q2: liked the agent-layer thesis but added
  nationalization as a tail risk, especially as AI risk awareness goes
  mainstream post-Mythos-tier capabilities. Q4: rejected v1 — "Dwarkesh asked
  how to *not get sidestepped*, not how to climb into the chain"; v1 assumed
  hyperscalers stay private, profitable, and free to operate as foreign
  multinationals on Indian/Nigerian soil, which is exactly what's at risk
  under cartelization or nationalization.

- **Added Q2 nationalization paragraph + Q4 v2.** Commit `0dda015`:
  - Q2 addendum: Atomic Energy Act 1946 / central-bank nationalization 1913 as
    historical analogues for governments seizing strategic private firms;
    nationalization probability rises monotonically with public AI-risk
    awareness.
  - Q4 v2 (kept v1 visible): sovereignty is leverage, not hosting. Three moves
    — (1) sovereign deployment via national AI gateway on the UPI/Aadhaar/ONDC
    template; (2) sovereign capital deployed as equity in the AI chain abroad
    (Norway GPFG analogue) — equity is portable, transmission lines aren't;
    (3) specialize in human-in-the-loop work AI cannot cheaply replace
    (evaluation, verification, embodied data, high-stakes review). Closing
    line: *"You don't avoid being sidestepped by selling the AI economy your
    dirt and your power — you avoid being sidestepped by owning a piece of it,
    mediating its access to your population, and specializing in what it still
    needs from you."*

## Key decisions
- Stardust prefers Q4 v2 framing (sovereignty as leverage, not infrastructure
  hosting). v1 left in the draft for now but should be cut before submission.
- Stardust authorized direct push to `dwarkesh-ai-2026` for each commit.
- Word count discipline deferred — accumulate ideas first, cut later.

## Open items for next session
- **Cut to 1,000 words.** Draft is 2,822 words; needs ~1,800 cut. Likely
  approach: keep v2 Q4, drop v1, trim or remove Q2 detour (it's still a
  separate question), tighten the meta-question framing.
- **Commit to one question.** The contest says pick one. Currently the draft
  spans Q4 framing → Q2 detour → Q4 nova v1 → Q4 nova v2. Decision pending on
  whether to keep the Q2 material at all.
- **Verify citations** flagged inline:
  - Stratechery / Ben Thompson on agent-layer switching costs
  - CMA foundation-models report (UK, 2024); Draghi Competitiveness Report
    (EU, 2024)
  - Atomic Energy Act 1946; Bank of England nationalization 1946
  - Per-capita electricity figures (IEA / World Bank)
  - KEPCO founding (1961); HUMAIN launch (Saudi PIF, 2025); G42 (UAE);
    IndiaAI Mission scope and budget
  - GPFG ~1.5% ownership claim (NBIM annual report); NPS AUM; NSIA AUM
  - UPI / Aadhaar / ONDC framing as digital public infrastructure (Nilekani,
    Carnegie India)
  - Sama / Scale AI offshore footprints
- **Address remaining issues from initial review** still unfixed:
  - Scott Aaronson vs. Scott Alexander labels (line 17 vs. 20)
  - "case case" duplicate (line 20)
  - "the would be" duplicate (line 20)
  - Citation format: contest rules require [1], [2] inline footnotes (per
    stardust's prior contest workflow); draft does not yet use this.
- **Pick one question for final submission** and prune the other.

## Commits this session (on `dwarkesh-ai-2026`)
- `042890e` Fix Tolstoy epigraph
- `f6a9b77` Fix typos and date in Q2 detour
- `ee49aaa` Add nova ideas for Q2 and Q4
- `0dda015` Add Q2 nationalization addendum and Q4 v2
