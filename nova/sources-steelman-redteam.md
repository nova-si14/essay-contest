# Sources: Steelman & Redteam by Argument
*nova, 2026-03-11*

Research to support or challenge each core argument in `drafts/arguments-003.md`.

> **Web access**: Web search is now available. The three primary sources (Hanson,
> Scott Alexander, Jones) have been researched live and have dedicated nova/ files.
> Entries marked `[VERIFY]` still need stardust to check specific details.
> Deep summaries: see `nova/hanson-growth-modes.md`, `nova/scott-ai-abnormal.md`,
> `nova/jones-ai-rd.md`.

---

## A1 — "AI is a normal technology"
*Claim: AI will revolutionize but not transform society — no 10x GDP growth, no
Malthusian flip, no singularity. It is more like electricity or the internet than
like the Industrial or Agricultural Revolution.*

### Steelman (supports the claim)

**1. Robert Gordon, *The Rise and Fall of American Growth* (2016)**
Gordon argues that the great inventions of 1870–1970 (electricity, running water,
internal combustion engine) were fundamentally different from anything since — they
were one-time improvements in the human condition that cannot be repeated. He is
skeptical of the transformative potential of information technology and AI, arguing
that productivity growth will remain modest. Directly supports the "AI is normal"
thesis by showing how hard it is for a technology to truly shift the growth
trajectory. `[VERIFY: Publisher Princeton UP; also available as NBER working paper]`

**2. Daron Acemoglu, "The Simple Macroeconomics of AI" (2024)**
Acemoglu (MIT, Nobel 2024) argues that AI's impact on GDP over the next 10 years
will be modest — somewhere in the 0.5%–1.0% range of GDP growth. His reasoning:
AI will automate only a limited set of tasks (those that are vision/language heavy),
and the tasks that most drive productivity growth are not easily automated. He
distinguishes between "so-so automation" (which replaces workers but doesn't
generate net growth) and genuine innovation. Strong steelman because it comes from
a Nobel laureate who has formally modeled the AI-growth relationship.
`[VERIFY: Published as NBER Working Paper 32487, April 2024]`

**3. Paul David, "The Dynamo and the Computer" (1990)**
David's influential paper on the "electricity paradox" shows that there was a
~40-year lag between the invention of electricity (1880s) and its measurable
impact on productivity (1920s). The lag was caused by the need for complementary
reorganization of factories, infrastructure, and skills. This is the classic
"normal GPT" argument: revolutionary technology arrives, creates bubbles in the
short run, then eventually delivers but much slower and less dramatically than
promised. Extremely relevant as the key historical analogy.
`[VERIFY: Published in American Economic Review Papers & Proceedings, May 1990]`

**4. Bresnahan & Trajtenberg, "General Purpose Technologies" (1995)**
Coined the term "General Purpose Technology" (GPT) for technologies that improve
over time, can be used broadly, and generate innovation spillovers. Key point: GPTs
DO transform the economy — but they do so gradually over decades, not explosively.
The authors list electricity, the steam engine, and IT as the canonical GPTs. AI
fits this definition perfectly. This literature supports "normal" in the sense that
GPTs are genuinely transformative *but* the transformation takes generations.
`[VERIFY: Published in Journal of Econometrics, 1995]`

**5. Erik Brynjolfsson, Daniel Rock, Chad Syverson — "The Productivity J-Curve" (2019)**
These economists argue we are in the *trough* of a J-curve: AI's costs are immediate
and measurable, but its productivity gains require organizational restructuring that
hasn't happened yet. The eventual gains will be real but will take 10–20 years to
fully materialize. This supports the "normal technology" view: AI delivers, but on
the timescale of electrification, not overnight.
`[VERIFY: Published in AEA Papers and Proceedings, 2019]`

**6. Tyler Cowen & Ben Southwood, "Is the Rate of Scientific Progress Slowing Down?" (2019)**
Argues that science has been getting harder — each discovery requires more
researcher-years and produces fewer breakthrough-per-researcher. This provides a
backdrop against which to evaluate AI's ability to accelerate science. Even if AI
helps, it may simply offset declining research productivity rather than produce
net acceleration. `[VERIFY: Published as a working paper / blog post at Marginal Revolution]`

**7. Benjamin F. Jones, "Artificial Intelligence in Research and Development" (NBER, 2025)**
The strongest formal steelman for "AI is normal technology." Jones shows that AI's
impact on R&D is determined by three factors: share of tasks AI performs, AI
productivity, and bottleneck strength. Key finding: "Marginal returns to intelligence
appear strongly limited when the intelligence operates on only a minority of tasks."
Transformative AI requires automating ~50%+ of research tasks — which is impossible
in fields with physical/regulatory bottlenecks (drug trials, materials synthesis).
Exception: pure math and software, where AI CAN be radically transformative (but
these are small fractions of the economy). Deep summary: `nova/jones-ai-rd.md`.
Source: https://www.nber.org/books-and-chapters/economics-transformative-ai/artificial-intelligence-research-and-development

---

### Redteam (challenges the claim — argues AI is abnormal)

**1. Scott Alexander, "AI as Profoundly Abnormal Technology" (AI Futures Project, July 2025)**
The essay the essay must directly engage with. Alexander argues AI differs from all
prior technologies because of **generality + human-similarity**: it integrates into
workflows like a paralegal, bypassing the institutional gatekeeping that slowed
electricity, cars, and the internet. Diffusion data: 40% of US adults, 76% of
doctors, 79% of legal professionals, 62% of programmers within ~2 years of ChatGPT.
He argues this unprecedented diffusion speed sets the stage for recursive
self-improvement → superintelligence within 2–10 years. Deep summary:
`nova/scott-ai-abnormal.md`.
Source: https://blog.ai-futures.org/p/ai-as-profoundly-abnormal-technology

**2. Robin Hanson, "Long-Term Growth as a Sequence of Exponential Modes" (2000)**
The formal mathematical case for "abnormal" technology. Three growth modes with
doubling times: Hunting (~224,000 yr), Farming (~900 yr), Industry (~15 yr) — each
~100x faster than the previous. If AI triggers a fourth mode transition, the
doubling time drops to weeks or days. This is the most rigorous quantitative version
of the transformationist case, and it provides the vocabulary for the essay's
"normal vs abnormal" definition. David Roodman's 2022 SSRN follow-up found the
hyperbolic fit even stronger with updated data. Deep summary:
`nova/hanson-growth-modes.md`.
Source: https://mason.gmu.edu/~rhanson/longgrow.pdf

**3. Dario Amodei, "Machines of Loving Grace" (October 2024)**
Amodei argues that within 7–12 years, AI could compress the equivalent of
"100 years of biology research" into a decade — a 10–15x multiplier on scientific
productivity. This is directly countered by Jones's bottleneck analysis: clinical
trials, physical synthesis, and regulatory requirements cap the actual acceleration
regardless of AI's cognitive power.
`[VERIFY: Published on Amodei's personal Substack, October 2024]`

**4. Leopold Aschenbrenner, "Situational Awareness" (June 2024)**
165-page document arguing AGI likely by ~2027, superintelligence by ~2030 via
continued scaling. The most detailed recent "abnormal" case from the AI safety
community. Source: situationalawareness.ai

---

## A2 — P(B|N) ≈ 1: AI is a bubble if it is normal technology
*Claim: Given the Goldfarb & Kirsch four-factor framework, a normal technology with
high uncertainty, compelling narratives, pure-play firms, and retail/novice investors
will almost certainly produce a financial bubble.*

### Steelman (supports the claim)

**1. Goldfarb & Kirsch (2019) — all four conditions present for AI**
- *Uncertainty* ✓: No consensus on AI business models. Even leading AI companies
  (OpenAI, Anthropic) are running at massive losses. The path from frontier models
  to sustained profitability is unclear.
- *Narratives* ✓: AGI narrative is the most compelling technology story since
  the internet. It has religious/eschatological qualities (singularity, doom) that
  amplify emotional investment.
- *Pure Plays* ✓: OpenAI, Anthropic, Mistral, Inflection, Character.ai, etc. are
  companies whose entire value is tied to the AI thesis with no diversification.
- *Novice Investors*: Mixed — see weakness note below.

**2. Michael Burry — Cassandra Unchained posts (already cited as [3][4])**
Burry has explicitly compared the current AI investment environment to previous
bubbles. His "supply" argument (footnote [4]) notes that easy funding conditions
create excess supply of a technology, which ultimately destroys pricing power.
Relevant to AI: massive compute buildout may create excess capacity that cannot
be monetized.

**3. Sequoia Capital — "AI's $600B Question" (2024)**
Sequoia estimated that the AI ecosystem would need to generate $600B in revenue to
justify current data center investment. As of 2024, total AI revenue was far below
this. This is essentially a calculation of the revenue gap — the difference between
what the market is pricing and what companies are actually capturing. Direct
evidence of bubble conditions.
`[VERIFY: Published as a blog post on Sequoia's website, September 2024]`

**4. Gary Smith & Jeffrey Funk, various AI skepticism papers (2023–2024)**
Smith and Funk have published a series of skeptical pieces on AI's ability to
generate economic value at the scale implied by current valuations. They focus
on the gap between demo performance and real-world reliability.
`[VERIFY: Published in various venues including Sloan Management Review]`

### Redteam (challenges the claim)

**1. "Some bubbles are real investments" — Amazon and the dot-com crash**
Amazon's stock fell 95% in the dot-com crash. It was technically in a bubble.
But investors who held through to 2025 made extraordinary returns. The point:
being in a bubble doesn't mean the underlying technology is worthless or that
all companies in the space are overvalued. The essay needs to address this
carefully — the P(B|N) = 1 claim is about *aggregate market expectations* being
too high, not about zero companies surviving.

**2. Nvidia's actual profitability (2024–2025)**
Unlike most bubble companies, Nvidia is generating substantial real profits.
Revenue grew from ~$26B (2023) to ~$130B (2025), with high margins. This is
unusual for a bubble company. However, the counterargument is that Nvidia is the
"picks and shovels" company (like railroad equipment manufacturers), which did
very well in the railroad bubble before overcapacity arrived.
`[VERIFY: Nvidia financial results; check exact revenue figures]`

**3. Goldman Sachs, "Gen AI: Too Much Spend, Too Little Benefit?" (2024)**
Interestingly, Goldman's own report (which is skeptical of AI ROI) also documents
real productivity gains in specific white-collar tasks. This complicates the "pure
bubble" narrative — there IS some real value being created, just perhaps not at
the scale implied by valuations.
`[VERIFY: Published as Goldman Sachs Economics research, June 2024]`

**4. "Novice investor" condition may be weak for AI**
Unlike the dot-com bubble (which had widespread retail participation via E*Trade
etc.) or the crypto bubble, AI investment is heavily concentrated in VC, large
tech companies (Microsoft $13B into OpenAI, Google $2B into Anthropic), and
institutional investors. If the "novice investor" condition isn't clearly met,
P(B|N) < 1 under the strict Goldfarb/Kirsch framework. The essay needs to address
this directly.

---

## A3 — Prediction markets are susceptible to bubbles under uncertainty
*Claim: Under high uncertainty, prediction markets develop correlated biases from
shared narratives, making them unreliable for identifying bubble conditions.*

### Steelman (supports the claim)

**1. Wolfers & Zitzewitz (2004) — "Prediction Markets"**
Already cited in stardust/prediction-markets.md. The paper notes:
- People overvalue small probabilities and undervalue near-certainties
- Personal/tribal biases affect trading (betting the home team, political markets)
- The paper explicitly notes bubbles are theoretically possible but rare
The small-probability overvaluation is directly relevant: if the "AI transforms
everything" scenario has, say, a 10% real probability, markets might price it at
30–40%.
`[VERIFIED: Published in Journal of Economic Perspectives 18(2), 2004]`

**2. Shleifer & Vishny, "The Limits to Arbitrage" (1997)**
Even if a mispricing exists, correcting it requires capital that rational arbitrageurs
may not want to commit — because the mispricing can get worse before it gets better.
In a prediction market with a long horizon (e.g., "will AGI arrive by 2030?"),
the cost of being right too early is holding a losing position for years. This
creates a structural barrier to correction of upward bias.
`[VERIFY: Published in Journal of Finance, March 1997]`

**3. Nassim Taleb on tail risks and prediction markets**
Taleb has argued that prediction markets (and probabilistic thinking generally)
systematically misprices tail events — especially events with no clear time horizon.
AI "transformation" is exactly this kind of event: unbounded upside, unclear timing.
`[VERIFY: Scattered across Taleb's books, particularly The Black Swan (2007) and
Antifragile (2012)]`

**4. Long horizon degrades accuracy — consistent with Scott Alexander's FAQ**
The stardust/prediction-markets.md file already captures Scott's acknowledgment
that superforecasters outperform prediction markets specifically on "questions so far
in the future that financial incentives start to lose force." This is an admission
that prediction markets lose calibration on long-horizon questions. AGI timelines
(10–30 year horizon) are exactly the type of question where this applies.

### Redteam (challenges the claim)

**1. Prediction markets outperform expert consensus historically**
Tetlock & Mellers (2014), the Iowa Electronic Markets for elections, and various
other studies show prediction markets beating expert panels. The general finding
is that market aggregation corrects individual biases *on average* even if not
every individual bet is calibrated.
`[VERIFY: Tetlock & Mellers published in Psychological Science, 2014]`

**2. No short-selling restriction in prediction markets**
Unlike equity markets (where short-selling is expensive and regulated), prediction
markets allow anyone to "sell" a position freely. This should in theory eliminate
bubble dynamics — there's no asymmetry between longs and shorts. The Shleifer &
Vishny limits-to-arbitrage argument applies less strongly here.

**3. Robin Hanson on futarchy and information aggregation**
Hanson argues that prediction markets are superior to *all* other information
aggregation mechanisms specifically because they provide monetary incentives for
truth-telling that expert panels and surveys lack. If the prediction markets say
AI is transformative, and Hanson's framework is right, the epistemic default
should be to trust the markets.
`[VERIFY: Hanson, "Shall We Vote on Values, But Bet on Beliefs?" (2006)]`

**4. The market for AGI predictions is small and illiquid**
Most AI timeline prediction markets have very thin liquidity. Small markets can
be moved by a single large actor (e.g., an AI company wanting to signal confidence
in its product). Low liquidity prediction markets are known to be less calibrated
than deep markets.
`[VERIFY: This is general prediction market knowledge; specific AI market sizes
would need current data]`

---

## A4/A5 — Are superforecasters biased toward AI optimism?
*Claim (A4): Superforecasters may just be good at replicating prediction markets,
so they inherit the same uncertainty-induced upward bias on AI.
Counter-claim (A5): Superforecasters might actually have a lower P(doom) than
prediction markets, in which case there is no conflict with A1.*

### Steelman for A4 (superforecasters are biased)

**1. Selection effects into "rationalist" communities**
The people who tend to become superforecasters, Metaculus contributors, or Good
Judgment Project participants skew heavily toward tech-adjacent, rationalist, and
EA-adjacent communities. These communities are deeply invested (financially and
intellectually) in AI being transformative. This is a classic in-group bias that
even Bayesian reasoners find hard to escape.

**2. "Galaxy-brained" reasoning risk**
LessWrong literature (e.g., Eliezer Yudkowsky) identifies a failure mode for
smart reasoners: constructing a long chain of plausible steps that leads to a
wild conclusion. Because each step seems reasonable, the final conclusion appears
justified. AI doom arguments are exactly the kind of argument that is hard to
evaluate because the topic is novel and the argument is long. Smart forecasters
might be *more* susceptible to this failure mode, not less.
`[VERIFY: "Galaxy-brained" is a LessWrong term; the concept appears in multiple
posts including some by Scott Alexander]`

**3. Moskovitz/Effective Altruism community comment**
The draft mentions "Muskowitz" (likely Dustin Moskovitz, EA funder) noting that
"the smartest people" he knows are worried about AI doom. This is consistent with
selection bias: if the EA community systematically attracts both high-IQ people
AND people who believe AI is transformative, the correlation between intelligence
and AI concern within that community is not evidence that intelligence leads to AI
concern *in the general population*.
`[VERIFY: Stardust to confirm exact quote and source]`

### Steelman for A5 (superforecasters actually agree with the author)

**1. Metaculus median AI timelines have extended in recent years**
Historically, Metaculus community forecasts on AGI timelines have extended further
into the future (not shortened) as time has passed and AGI has not arrived. This
is weak evidence that superforecasters in aggregate may be more skeptical than
the narrative around "imminent AGI" suggests.
`[VERIFY: Check current Metaculus "date of transformative AI" question]`

**2. Tetlock's finding: superforecasters *don't* cluster in a single community**
Unlike the AI safety community, the Good Judgment Project's superforecasters were
recruited broadly from the general population. Their accuracy comes from method
(Bayesian updating, reference class forecasting) not from shared ideology. If this
is true, they would be *less* susceptible to the AI narrative than the EA community.
`[VERIFY: Tetlock & Gardner, Superforecasting (2015), Crown Publishers]`

**3. Live prediction market data (March 2026)**
Checked live. Key findings:
- **Metaculus**: median AGI date ~mid-2030; interquartile range 2027–2039; first
  general AI median = Feb 2028. (~1,700 forecasters)
- **Polymarket**: OpenAI AGI before end of 2026 = **14%** (86% say no).
  AI bubble burst by Dec 2026 = **17%** ($2.2M volume).
- **Key finding**: prediction markets are much more conservative than the AI narrative
  implies. The real "bubble" signal is in equity markets (Nvidia valuations), NOT
  in prediction markets. This actually partially supports A5: superforecasters and
  prediction markets don't strongly disagree with the author.
- **The interesting disconnect**: stock markets are far more bullish on AI than
  prediction markets. This is itself evidence of the stock market's greater
  susceptibility to bubble dynamics vs. prediction markets.

### Redteam (superforecasters are not biased; their AI views are reliable)

**1. Tetlock's core finding: foxes beat hedgehogs via method, not prior**
The core finding of *Superforecasting* is that good forecasters succeed by:
- Updating frequently on new information
- Using reference classes from outside the domain
- Avoiding narrative capture
These methods are explicitly designed to counter exactly the biases described in A4.
If the method works as Tetlock describes, superforecasters should be more reliable
on AI than the prediction markets.
`[VERIFIED: Tetlock & Gardner, Superforecasting (2015)]`

**2. Short 1-hour training effect suggests it's about method, not selection**
The draft already notes that a 1-hour training session improves forecaster
calibration significantly. This suggests superforecasting ability is more about
*process* than *intelligence* or *community membership* — which weakens the
selection bias argument. You don't need to be in the rationalist community to
forecast well.
`[VERIFY: This finding appears in Tetlock's research; confirm exact study]`

---

## Primary Source Files

Deep research summaries for the three main sources are in:

- `nova/hanson-growth-modes.md` — Hanson (2000): growth modes, doubling times, fourth mode prediction
- `nova/scott-ai-abnormal.md` — Scott Alexander (2025): diffusion speed, generality, recursive improvement
- `nova/jones-ai-rd.md` — Jones (2025): three-factor framework, bottleneck finding, field-by-field analysis

---
*Entries marked `[VERIFY]` need independent confirmation by stardust via direct web access.*
