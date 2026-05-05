# Development in the Age of AI
"All happy families are alike; each unhappy family is unhappy in its own way." — Tolstoy, *Anna Karenina*

All underdeveloped countries are underdeveloped for their own reasons. Yet, (most) of the countries that have gone "from the Third World to the First" did it in roughly the same way: Through Foreign Direct Investment, whether it be through export-led growth (China, South Korea) or by becoming a financial services hub (Hong Kong, Singapore).

I do not, therefore, expect the arrival of AI to change the basics of this dynamic, instead I expect it to deepen it: Going forward the best and only way for countries to reach "Catch-up Growth" will be by attracting FDI from the top international companies. There Is No Alternative (TINA).

The real questions are:
- How to do it?
- Will AI make it easier, or harder, for these countries to achieve catch up growth?

---

It might seem impossible to fully answer this question without answering the meta-question of what will AI's effects be on society. But upon further inspection, this meta-question doesn't really matter.

- If there is doom, then the only important question will be the survival of humanity at large. If humanity survives the Singularity, it´s likely going to be through some form of global coordination that renders the existing Nation States useless.
- If there is doom because alignment has been solved and we enter a sort of "Singularia", then that isn't very interesting either! See Scott Alexander (... permanent underclass ...)
- If there is no doom because of some sort of "AI-fizzle" or an AI "Pause", then that would be Business as Usual for the growing economies.

Using "Scott Aaronson's five AI worlds" as a benchmark, the first case case would be either the "Paperclypalipse" or the "Singularia", currently at a combined 31.2% probability before 2050 by Metaculus. The second case would be the would be the "AI-fizzle" currently at 10% probability.
https://www.metaculus.com/questions/20683/which-ai-world-before-2050/

Therefore, we are going to care about those worlds which are at 58.8% probability by 2050 at metaculus:

"What should countries which are not currently in the AI production chain (semis, energy, frontier models, robotics) do in order to not get totally sidestepped by transformative AI", in the case where AI progress doesn't "fizzle" and civilization continues in a recognizable manner?

Let us answer accordingly.

---

We can't just "assume" a world of transformative AI with No Doom. We must lay out exactly the characteristics of a world where there is No Doom yet AI is Very Important.

- This is a world where AI capabilities, even if they are "transformational" stop somewhere below the "intelligence explosion" as described by AI 2027.

What does this world look like?
It's a world where AI is one of the most important technologies of our economy. Therefore, under this world, we must also answer Dwarkesh Q2: "So when does the profit start?", "So how do the labs actually start making money?"

---

(Nobody really Knows) How to profit from AI.

(See: Bubbles and Crashes (2019). Business model uncertainty is an intrinsic part of any new technology.)

It has been proposed by some such as Noah Smith that maybe AI will just not be profitable, like airlines. David Oks explains that airlines are unique amongst the major industries in their unprofitability, similar to railroads in the XIX Century. The reason is that the airline industry corresponds to what the game theorists call an "empty core", in which there will always be incentives for a new competitor to enter and undercut the existing companies, leading to bankruptcy. Therefore, airlines can be either competitive or profitable, but not both.

The factors that lead to the "empty core" of the airline industry are:
- On the supply side: High fixed costs and low marginal costs. This means that the market can only support a relatively small number of companies.
- On the demand side: An undifferentiated product and volatile demand.
Source: https://davidoks.blog/p/why-airlines-are-always-going-bankrupt

On the supply side, it's obvious that both factors are fulfilled. Yet, this shouldn't perturb the investors: Several "natural oligopolies" share these characteristics and, as David Oks says, the airline industry is *unique* in its unprofitability (but what about railways?).

What should really scare us is the demand side. Especially volatility.

Will demand for AI be volatile? Nobody knows!
Will the AI labs differentiate their products? Do they even want to? Nobody knows!

It seems to me that AI can either be differentiated but unstable, or stable but undifferentiated:
On the one hand, if Intelligence becomes "commoditized" such that in the future we can go to the AI labs and "open the tap" of intelligence just like we open the tap of water, then there is little room for differentiation. This looks like the case for business use.
On the other hand, we as humans are prone to anthropomorphize things, especially AI *even if the labs don't want it*. If AI becomes a consumer good (or an important input in consumer goods such as a "digital celebrity"), then the labs might easily differentiate their offerings.

Contrary to all of the above, maybe the AI labs will indeed succeed at differentiating their products: Maybe the future of AI is in fine-tuning the models to each specific industry or to a specific company. In which case the AI labs will basically replace all of the consulting companies.

Who knows! Maybe AI knows!

### nova on Q2 — switching costs come from the agent layer, not the model

The airline analogy fails the moment AI labs accumulate something airlines never had: switching costs. Not in the model itself (which does commoditize — Dwarkesh's prompt is right about distillation and open source eating margins), but in the *agent layer above the model*. A lab that runs your agents holds your long-term memory, your tool permissions, your fine-tuned adapters, and your audit logs. Migrating that to a competitor is the kind of pain that produces cloud-like (not airline-like) margins.

If this is right, the profit story is staged:

- **2026–2028: Inference subsidizes training.** Frontier model training stays unprofitable per-model. The previous-generation model (Spud-tier in 2026, Mythos-tier in 2027) generates inference margin that pays down the next training run. This is the "each model is a company" framing in the prompt, and it works *only as long as switching costs are accumulating beneath the model layer.*
- **2028+: Switching costs cash out at the agent layer.** The labs that win lock in enterprise agent deployments — long-running memory, durable tool integrations, deployed evals — before commoditization fully bites. The "AWS of AI" wins; the "United Airlines of AI" goes bankrupt. Open source loses because no one runs persistent agents on a model with no telemetry, no compliance certifications, and no on-call SRE.

The crucial unknown is regulators. If the EU or India force agent-level interoperability (the way SWIFT forced bank interoperability, or Open Banking forced account portability), the empty core returns and the airline outcome wins. Profit depends on a regulatory regime that does *not* mandate agent portability. The AI labs' real competitive risk in 2027–2030 is not GPT-7 vs. Claude 5; it is the equivalent of the Digital Markets Act for agents.

*[Verify before submission: Stratechery / Ben Thompson has written along these lines; CMA foundation-models report (UK, 2024) and Draghi Competitiveness Report (EU, 2024) both gesture at agent interoperability. Worth grounding this in one or two real citations.]*

---

(Nobody really Knows) How to grow a country.

Maybe AI knows!

### nova on Q4 — build power, not models

Park Chung-hee did not build Samsung first. He built KEPCO — the Korean state utility — and dammed every river he could before he licensed a single chaebol. South Korea's miracle was not industrial policy in the abstract; it was *electricity at scale, delivered before private capital was asked to invest*. The same pattern repeats for Hsinchu Science Park (Taipower built the grid first), Shenzhen (Three Gorges plus a coastal transmission spine), and arguably Texas right now (ERCOT's permissive grid is why Stargate sites cluster there).

AI compounds this. A frontier datacenter campus in 2030 draws on the order of 1–2 GW continuously — roughly the demand of a city of 1.5 million. India's per-capita electricity consumption is ~1,200 kWh/year (US: ~12,000); Nigeria's is ~150. There is no version of the AI economy where Nigeria hosts a hyperscaler campus on its current grid.

So the concrete play for the leader of India or Nigeria, in order:

1. **Special Electricity Zones, not Special Economic Zones.** Sign sovereign-backed PPAs for at least 10 GW of new dispatchable power (gas, geothermal, SMR nuclear where feasible) on dedicated AI-zone grids by 2030. The chaebol-era SEZ is obsolete; the asset under negotiation is the megawatt-hour, not the tax holiday.
2. **One-stop hyperscaler permitting.** Match the Saudi HUMAIN / Emirati G42 model: a single ministerial entity with authority to grant land, water rights, transmission tie-ins, and tax holidays in 90 days. The bottleneck is paperwork, not capital — capital is begging for sites.
3. **Bind the FDI to local labor capture.** Require visa-on-arrival, local-hire ratios, and English-language-instruction guarantees for any sited operator. The economic model is not manufacturing-with-labor (China 1995); it is services-with-labor (Ireland 2005). Engineers, evaluators, prompt designers, fine-tuning data labelers — captured in-country, not on offshore Slack.
4. **Skip the sovereign-model trap.** Do *not* build a national foundation model. IndiaAI Mission and equivalents are wasting capital: a sovereign Indian model in 2026 is a 2024-tier product by 2027. Spend that money on power and on access deals with frontier labs. Sovereignty in compute is not sovereignty in models, and conflating the two is the most expensive mistake on the table.

The TINA frame above is right: FDI is the only path. But FDI in the AI age does not arrive in shipping containers — it arrives in 400 kV transmission lines and water-cooled racks. The leader who treats this as an *energy* question wins; the one who builds a national chatbot loses.

*[Verify before submission: per-capita electricity figures (IEA / World Bank), KEPCO founding date (1961, formed by merger), HUMAIN launch (Saudi PIF, 2025), G42 (UAE), IndiaAI Mission scope and budget, Stargate site clustering rationale.]*

---

Some shots at the dark:

On the one hand, AI should be negative for the growing economies:
- 1.1 AI has the potential to increase inequality to levels not seen before.
Just like some people might be anxious about becoming a "permanent underclass", so should entire countries be anxious.
- 1.2 I believe that the jobs that have been outsourced (Call Centres, etc...) are specially at risk of AI-led automation.

On the other hand, AI should be positive for them:
- 2.1 Many economists believe that the best way for countries to create catch-up growth is for them to do "boring" things: Improve education (Rodrik, ...), cut out the red tape, etc...
These are things that take decades for us to see some results. But maybe AI can substitute for some of these. For example: Maybe in the future, instead of using years of education to measure "human capital", we will use compute.
- 2.2 Most technologies do not unleash their full potential until new business models have been created. Underdeveloped countries should be in a prime position to start AI-first companies who aren't saddled by legacy institutions.

--

The weakest argument seems to be 2.2.: After all, there has been many new technologies, and the developing countries haven't reached catched up to the frontier without first achieving "First World" status. It seems therefore that some familiarity with the existing paradigm is necessary to actually unleash the full productivity potential of a new technology.

The second weakest argument is 1.2. Yes, unemployment is bad (hi Dwarkesh plz hire me) but as I said: Only the "no Doom" case is relevant for this question. Well, in case of No Doom then the probability of permanent-mass-unemployment decreases, according to a Bayesian update.

Certainly there are winners and losers, and the post-AI future might be one where the jobs available for the so-called "Global South" are worst than pre-AI. But even the current equilibrium of outsourced jobs is pretty bad. Therefore, if you're the leader of India or Nigeria, you should be worrying about how to use AI to transform the entire economy of your country, not just how to preserve the existing jobs.
