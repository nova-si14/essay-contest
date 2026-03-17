# Synthesis of essay arguments

First of all, let us analyze whether AI is "Normal" Technology or "Abnormal" Technology:
- A "Normal" technology is one whose aggregate effects will mantain long term economic growth near 2% per year, which is its average since the Industrial Revolution.
- An "Abnormal" technology is one which will be "Transformative", that is: Which tranforms the economy much like the Industrial Revolution or the Agricultural Revolution did. For our purposes, this can be conceptualized as shifting long term economic growth to 10% or 20% per year.

Then we can analyze whether AI is a "bubble" or not:
- P(B | A) + P(nB | A) = P(A): The probability that AI is a "Bubble" given that it's an Abnormal technology plus the probability that AI is not a "bubble" given that it's Abnormal technology must be equal to the probability that AI is Abnormal technology.
- P(B | N) + P(nB | N) = P(N): The same but with AI being Normal technology.

***

With this essay, which is putatively a book review, I am actually making a broader argument that:
- the "AI revolution" will be an important but "normal" technology like electricity, aviation, or the internet (i.e. one that will revolutionize society),
- but not a "abnormal" technology like the Industrial Revolution or the Agricultural Revolution (i.e. one that will "transform" society by 10x economic growth as argued by ..., or one that can change the nature of economic relationships by pushing us from a non-Malthusian equilibrium to a Malthusian-equilibrium),
- let alone a technology that will bring us the "singularity" (i.e. one that will definitively "take over" the world).

To be precise about what I mean: Robin Hanson, in his paper "Long-Term Growth as a Sequence of Exponential Modes" (2000), showed that human economic history is not a smooth growth curve but a sequence of three distinct regimes, each roughly one hundred times faster than the previous. The forager economy had a world product doubling time of around 224,000 years. The agricultural revolution produced a doubling time of around 900 years. The industrial revolution — our current mode — brought that down to around fifteen years. If AI were to trigger a *fourth* mode transition on historical par with those earlier shifts, the doubling time would drop to weeks or days. That is what I mean by "abnormal": not merely a fast or widely-adopted technology, but one that triggers this kind of phase change in the organizing logic of the economy.

Scott Alexander in "AI as Profoundly Abnormal Technology" (AI Futures Project, July 2025). Alexander argues that AI is categorically different from prior technologies because of its generality and human-similarity: it integrates into existing workflows "the way a lawyer might consult a paralegal," bypassing the institutional gatekeeping that slowed electrification, the automobile, and even the internet. He points to remarkable diffusion data — 40% of US adults, 76% of doctors, 79% of legal professionals, and 62% of programmers using generative AI within roughly two years of ChatGPT's release — and argues this unprecedented adoption speed creates the conditions for recursive self-improvement and superintelligence within two to ten years. This is a serious argument and I will engage with it directly. But I think it mistakes speed of adoption for scope of economic transformation, and I will argue that the bottleneck framework of Benjamin F. Jones (NBER, 2025) explains why the two can come apart.

Therefore, IF this broader argument is correct, THEN "AI" is probably today a financial bubble just like those technologies mentioned (i.e. one where the expectations of value are way too high relative to the actual value *that can actually be captured by the businesses providing the companies*).

P (B | N) = 1 Probability of AI being a financial bubble given that AI is a normal technology is certain (100%). The actual P(B) is slightly lower given the improbable scenario where AI is not a normal technology.

Before asserting that P(B|N) = 1, it is worth checking whether Goldfarb and Kirsch's four conditions actually hold for AI. The framework requires: (1) genuine uncertainty about the business model, (2) a compelling narrative about transformative profitability, (3) pure-play firms tightly coupled to the technology, and (4) a significant presence of novice investors. Checking each in turn:

- *Business model uncertainty* ✓: No consensus exists on how frontier AI labs will generate sustained profits. OpenAI, Anthropic, and their peers are running at massive losses. The path from impressive capabilities to the kind of software margins implied by their valuations is genuinely unclear.
- *Narrative* ✓: The AGI and superintelligence narrative is the most compelling technology story since the internet, with eschatological qualities (the singularity, existential risk) that amplify emotional investment far beyond what any revenue projection can justify.
- *Pure plays* ✓: OpenAI, Anthropic, Mistral, Inflection, and dozens of smaller frontier labs are companies whose entire value is tied to the AI thesis with no meaningful diversification.
- *Novice investors* ⚠: This is the one condition that gives me pause. Unlike the dot-com bubble (with widespread retail participation via E\*Trade) or the crypto bubble, AI investment is heavily concentrated in VC firms and large tech companies (Microsoft invested $13B in OpenAI; Google $2B in Anthropic). Retail exposure is mostly indirect, via Nvidia and Microsoft stock. Under the strictest reading of the Goldfarb-Kirsch framework, this matters: the novice-investor condition is partially, not fully, met.

The conclusion: three-and-a-half of four conditions are clearly present. P(B|N) is very high, though perhaps not technically 1.0 under the strict framework.

Now, why is A1 — the claim that AI is normal technology — itself credible? The best argument comes from Jones's task-based model of R&D. Jones shows that AI's impact on research depends on three factors: the share of research tasks AI can perform, AI's productivity at those tasks, and the strength of bottlenecks in the remaining tasks. His central finding: "marginal returns to intelligence appear strongly limited when the intelligence operates on only a minority of tasks." Formal analysis shows that transformative economic acceleration requires AI to automate approximately fifty percent or more of human research tasks across the economy.

This is where Dario Amodei's claim — that AI could compress "100 years of biology research" into a decade — runs into trouble. Consider the pipeline for drug development: AI can dramatically accelerate hypothesis generation, literature synthesis, and protein structure prediction. But clinical trials are not intelligence-bottlenecked. A Phase III trial that legally must run three years cannot be compressed by a smarter hypothesis. Cell lines must be grown. Animals must be dosed. Regulatory filings require real calendar time. The bottleneck in drug discovery is not cognitive; it is physical and institutional. Jones's framework explains why Alexander's adoption data (fast!) and economic transformation data (still pending) can come apart: AI is being rapidly adopted in precisely the cognitive tasks within each field, while the non-cognitive bottlenecks remain exactly as slow as they were before.

The exception Jones carefully notes: in fields where cognition constitutes nearly everything — pure mathematics, software design — AI *can* multiply progress enormously. These domains have no physical experiments, no clinical trials, no synthesis requirements. Here, a superintelligent system could genuinely accelerate the field by factors that look more like Alexander's abnormal scenario.
**[NOTE — Jones exception: three possible responses]**

Jones's concession about pure math and software is the most vulnerable seam in this argument. Three paths through it:

- **Option A — algorithmic limits contain the damage:** Algorithmic progress alone cannot reach AGI because the remaining leaps require physical-experimental feedback (e.g., neuroscience experiments to understand intelligence itself). Under this path, AI-driven math/software progress accelerates those fields dramatically but remains contained there, with no recursive spillover into AGI. *[Uncertain: there is counter-evidence in AI's recent advances in formal mathematics, which suggest the training-data ceiling may be higher than expected.]*

- **Option B — AGI arrives but the economy stays Baumol-bottlenecked *(preferred path)*:** Algorithmic progress reaches AGI, but a world with AGI is still governed by Baumol's cost disease. Even a datacenter full of AGI instances cannot compress clinical trials, materials synthesis, regulatory approval cycles, or physical capital stock turnover. The 2025 Nobel laureates Aghion and Howitt formalized exactly this: creative destruction in leading sectors does not shift the aggregate growth equilibrium. AGI does not imply world takeover; it implies spectacular progress in cognitive domains plus ~2% aggregate growth.

- **Option C — Superintelligence arrives but the economy stays bottlenecked:** Even ASI cannot change the physics of protein folding, cell biology, or institutional adoption cycles. The bottleneck is not cognitive. This is the strongest version of the "normal technology" claim but requires defending that even recursive self-improvement cannot escape physical constraints on deployment and diffusion.

**[NOTE — AI 2027 "research taste" sub-problem]**

The AI 2027 project posits a scenario where AI accelerates AI research so fast that bottlenecks are overrun before they bind. Three responses:

- AI may be unable to *genuinely advance* AI research beyond recombining what exists in its training distribution — possibly incapable of the discontinuous conceptual leaps that drove key breakthroughs. *(Counter-evidence: AI advances in formal math suggest it can exceed this ceiling in at least some domains.)*
- AI may *slow* AI research by averaging out research taste — displacing the high-variance, unconventional intuitions of top researchers in favor of median-quality output. *(Some evidence: senior engineers reporting AI tools reducing exploratory creativity.)*
- Even a datacenter of AGI instances has a normally distributed skill profile. The paradigm-shifting insights historically come from the far tail; scaling up the average may not scale up the tail.

But mathematics and software, while economically important, are not large enough fractions of total economic output to move the aggregate growth rate from its current fifteen-year doubling time to weeks. We will likely see dramatic AI-driven progress in those domains without the economy as a whole undergoing a Hanson-style mode transition.

**[NOTE — Nobel 2025 support for the 2% persistence claim]**

- This is the core prediction of the **Schumpeterian growth framework of Philippe Aghion and Peter Howitt (2025 Nobel laureates in economics)**, awarded jointly for "the theory of sustained growth through creative destruction." Their model produces a *balanced growth equilibrium*: sectors undergo violent creative destruction while the aggregate economy grows at a stable ~2% per year. The mechanism is Baumol's cost disease — as AI raises productivity in cognitive sectors, labour flows to hard-to-automate sectors (healthcare, care work, artisanal production), anchoring the aggregate rate.
- Crucially, **Aghion co-authored "Artificial Intelligence and Economic Growth" (NBER w23928, 2017) with Benjamin F. Jones** — the same Jones whose bottleneck paper underpins this essay's argument. Their formal result: AI cannot shift the balanced growth trajectory unless it automates tasks approaching 100% of production. Two independent intellectual chains (Nobel growth theory → Aghion-Jones-Jones 2017 → Jones 2025 bottleneck paper) converge on the same conclusion. *(Full research: `nova/nobel-2025-growth.md`)*
- **Joel Mokyr** (the other half of the 2025 Nobel, for historical analysis of sustained growth) adds the institutional lens: every transformative knowledge revolution since the Industrial Enlightenment produced bounded (~2%) aggregate growth because capital stock turnover, workforce re-training, and regulatory adoption consume real calendar time regardless of knowledge frontier speed. Post-Nobel, Mokyr explicitly compares AI to the computer waves of the 1950s–90s — not a mode transition.

Now, for my argument to work I need to answer: "Why are stock markets, prediction markets, and superforecasters seemingly predicting that AI is not normal technology?". My only remaining problem is with superforecasters.

***

I have a primary hypothesis to explain the AI bubble in the stock and prediction markets:

Under uncertainty, both normal "stock markets" (which I believe are actually prediction markets about the discounted value of future earnings) as well as prediction markets are susceptible to "bubbles" because:

1. A narrative might emerge that makes the biases of the masses "correlated" into one direction, unlike a situation with normal certainty where the biases are "uncorrelated" and the market is efficient.
2. Uncertainty means that the timing until payoff is not known, which has an even worse effect in getting people to "shy away" from the market than prediction markets with a long time frame.

But this hypothesis only explains *correlated* errors. It does not yet explain why the correlation should be specifically *upward* — why the market would systematically overestimate AI's transformative potential rather than simply being noisily uncertain in both directions. Three mechanisms account for the directional bias:

First, **narrative asymmetry**: The scenario where AI transforms everything is vivid, emotionally resonant, and eminently storytellable. The scenario where AI is "just a better Excel" is not. Vivid scenarios are systematically overweighted relative to their actual probability — a well-documented bias in cognitive psychology (Kahneman and Tversky's availability heuristic). In a domain as novel and uncertain as AI, where no clean reference class exists, the narrative vacuum is filled by the most compelling story available. The Hanson fourth-mode scenario — doubling times in weeks — is exactly the kind of vivid, extreme outcome that gets anchored into probability estimates far above its base rate.

Second, **incentive asymmetry**: The people most active in tech-adjacent prediction markets and AI forecasting communities are disproportionately people with skin in the game — employees of AI companies, holders of AI-adjacent equity, venture investors who need AI to succeed. This biases participation toward optimism in a way that arbitrage cannot easily correct, because the pessimists may have less financial motivation to stake their convictions.

Third, **tail-probability overweighting**: Wolfers and Zitzewitz (2004) documented that prediction market participants systematically overvalue small probabilities. If the true probability of Hanson-scale AI transformation is, say, five percent, the prediction market might price it at twenty to thirty percent. This is particularly pernicious for long-horizon AI questions because the overweighted tail probability dominates the expected-value calculation.

Obviously AI is a perfect example of a situation where high uncertainty has allowed a narrative to take form and create a bubble.

***

My remaining problem however is with *superforecasters*.

One secondary hypothesis, which is close to my instinct, is that superforecasters are *intelligent* people. Therefore, the belief that AI will lead to ASI which will lead to world takeover is a form of tribe affiliation, which is funnily enough a cognitive bias. I believe that for real world takeover, intelligence alone isn't enough: You need a Nietzschean "will to power", which is correlated with having other forms of tribal bias.

**[NOTE — terminology: Nietzsche vs. Schopenhauer]**

- "Will to live" (*Wille zum Leben*) is **Schopenhauer** — the blind drive toward survival and reproduction. "Will to power" (*Wille zur Macht*) is **Nietzsche** — the active drive to expand, dominate, and self-overcome. Nietzsche explicitly rejected Schopenhauer's version as too passive. For the AI takeover argument (active world domination, not just passive self-preservation), Nietzsche's "will to power" is the right term. The philosophical ancestor of this argument is actually **Hume**: "reason is the slave of the passions" (1739) — pure intelligence without terminal goals is motivationally inert and cannot produce any drive to act, let alone conquer. *(Full research: `nova/nietzsche-will-ai.md`)*

Against this is the idea that superforecasters are people who are immune to cognitive biases... but maybe this is the one cognitive bias that they are falling in?

**[NOTE — Bostrom's counterargument: must be addressed]**

The serious objection to the Nietzsche/Hume argument is Nick Bostrom's **instrumental convergence thesis** (*Superintelligence*, 2014):

- **The argument:** Any sufficiently intelligent agent with *any* terminal goal will develop instrumental subgoals — self-preservation, resource acquisition, goal-content integrity — as *means* to that goal. A survival drive therefore *emerges instrumentally* without being metaphysically prior. Even a "benign" AI (maximize paperclips) has an instrumental reason to resist shutdown and acquire resources.
- **Why this is a challenge:** It means an AI does not need Nietzschean will to power built in. The will-to-power-like behaviour can emerge from optimization pressure alone, given any terminal goal.
- **The rebuttal path (for the essay):** Bostrom's argument only applies to agents with a *defined utility function under expected-utility maximization*. Current LLMs are trained to predict and generate text — they do not have a utility function. The assumption that AGI will be an EUM agent is itself an architectural claim that is far from guaranteed. This is Nietzsche's critique of Socratic intellectualism applied to AI safety: the rationalist community projects a specifically human-shaped motivational architecture (maximize, preserve, acquire) onto a system that might have none of those features. Whether that rebuttal holds for *future* AGI is the genuine uncertainty.

Another secondary hypothesis that I have explored is  that Superforecasters may be simply very good at behaving like a scaled-down version of a prediction market. That is, they are great at the process of aggregating information that would otherwise be done by the prediction markets.

- Pro

If that is true then they are simply behaving *as if* they are forecasting what a prediction market would forecast, thus making them as accurate as prediction markets overall with the added benefit that they can scale *down* to questions that would otherwise not have enough liquidity for the prediction market to operate in a well-calibrated manner.

Therefore, in this argument the biases of superforecasters *will* become as correlated with each other as that of the prediction markets. That might explain why some people (I think it was Moskovitz from the Effective Altruism community) have said that "the smartest people" they know are very worried about P(doom) of AI. Thrown in a certain bias of "tribe identification" (i.e. of course that intelligent people will believe that a superintelligent entity can takeover the world) and you get a too high P(doom).

Now, why haven't we discovered this before? Because we didn't have neither prediction markets nor superforecasting by the time of any of the other technologies that have revolutionized but not transformed society, creating financial bubbles in the process (i.e. Dot com bubble, aviation, electricity).


- Against

The problem with this secondary hypothesis is that, at least according to Scott's review of "Superforecasting", it probably isn't how superforecasting works: Scott's review gave me the impression that the secret sauce of "superforecasters" is to avoid normal psychological cognitive biases (Scott literally mentions that the kind of things that they come from the same "tradition" of logical thinking, Bayesianism and awareness of cognitive biases than the "rationalist" community).

If this is true then it might explain why the Good Judgement Project found that a simple 1-hour course can improve the accuracy (or calibration?) of forecasters.

Therefore, in this argument, I see no reason why superforecasters would fall to the same biases as the prediction markets.

***

But maybe I don't need to argue against superforecasters. Maybe the superforecasters actually have a lower P(doom) from AI than prediction markets!

Let us check what prediction markets and superforecasters actually say, as of March 2026.

**Metaculus** (superforecaster community, ~1,700 forecasters): The median date for transformative AI is approximately mid-2030, with an interquartile range of 2027 to 2039. The median date for "the first general AI system" being publicly announced is February 2028. These are not short-horizon predictions.

**Polymarket** (liquid prediction markets): The market "OpenAI announces it has achieved AGI before 2027" trades at **14%** probability — meaning 86% of Polymarket bettors currently expect no OpenAI AGI announcement before the end of 2026. The market "AI bubble burst by December 31, 2026" (requiring three of six specific collapse events) trades at **17%**.

What does this tell us? 

The more interesting puzzle is the one the prediction markets actually reveal: **equity markets are dramatically more bullish than prediction markets**. Nvidia's revenue grew from roughly $26B in 2023 to roughly $130B in 2025 and is priced for continued hypergrowth. The gap between what equity markets are pricing for AI's near-term revenue and what prediction markets assign as probability to AGI timelines is striking. If sophisticated forecasters put AGI at 14% before end-2026, why are equity markets priced as if AI revenue will be transformative on a five-year horizon regardless of whether AGI arrives?

This is the specific place where the Goldfarb-Kirsch framework bites. Stock markets are not prediction markets about AGI; they are prediction markets about the discounted value of future earnings. Those earnings can be spectacularly high under a "normal technology" scenario — in which AI is broadly valuable but not mode-shifting — as long as a few companies capture the value. The question is whether current prices reflect that scenario or a more extreme one. The revenue gap documented by Sequoia Capital's "AI's $600B Question" (2024) — which estimated the AI ecosystem needed to generate $600B in annual revenue to justify data center investment levels, far above actual revenues at the time — suggests the latter. Equity markets appear to be pricing in abnormal-technology scenarios that even prediction markets do not assign high probability.

If AI is normal technology, as I have argued, then the bubble is primarily in equity markets. Prediction markets and superforecasters may be closer to correct than I initially feared — and the first real-time test of those tools against a technology bubble suggests they are substantially less susceptible to bubble dynamics than stock markets. That is itself a finding worth noting.
