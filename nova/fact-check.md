# Fact-Check Notes
*Prepared by nova, 2026-03-02*

Covers two areas flagged in `drafts/working-002.md`:
- (2b) The Electricity / Burry section (formerly annotated "all of the above needs fact checking")
- (3a) The 2% growth claim on line 19 (formerly annotated "(check)")

Sources used: `stardust/cassandra-unchained-by-human.md`, web search (AEA website, Novel Investor, companiesmarketcap.com), and training knowledge.

---

## Section 1 — Electricity / Burry section

### Claim-by-claim assessment

**1. "59 initial customers" electrified on September 4, 1882**
- STATUS: ✅ CONFIRMED
- Source: stardust file (quoting Burry directly); consistent with training knowledge.

**2. 10% of households by 1908 / 50% by 1925 / 90% by 1949**
- STATUS: ✅ CONFIRMED
- Source: stardust file. The stardust file also adds an intermediate figure (70% by 1930 and all households by 1960) that the draft does not use but is consistent.

**3. "Edison's company lost the right to electrify Chicago World's Fair"**
- STATUS: ✅ CONFIRMED
- Westinghouse won the 1893 World's Columbian Exposition contract. Source: stardust file, citing NYT, May 7, 1892 (primary source).
- Note: The contract was awarded in 1892; the Fair itself was held in 1893. The draft's phrasing ("as early as 1893, Edison's company lost the right…") implies it happened in 1893, but the award decision was 1892.

**4. Edison "forced into a merger by J.P. Morgan"**
- STATUS: ✅ CONFIRMED
- Edison General Electric merged with Thomson-Houston Electric Company in 1892, with J.P. Morgan orchestrating the deal, creating General Electric.
- Source: stardust file (line 35), corroborated by training knowledge.
- ⚠ CHRONOLOGICAL INCONSISTENCY IN DRAFT: The draft says Edison's company was "brought to its knees by the Panic of 1893, being forced into a merger." But the merger occurred in 1892, *before* the Panic of 1893. The Panic is therefore not the cause of the merger. The two events should not be sequentially linked as the draft implies. Recommend stardust review and correct this sentence.

**5. "General Electric lost 97% of its value" in the Great Depression**
- STATUS: ✅ CONFIRMED
- Web search (companiesmarketcap.com via Novel Investor data): GE peaked at $358.00 on September 30, 1929, and bottomed at $9.50 on June 30, 1932.
- Calculated decline: ($358 − $9.50) / $358 = **97.3%**
- This matches the Burry claim exactly.
- The draft adds "trading at its 19th century price" — GE was incorporated in 1892, so prices near $9–10 in 1932–1933 would be comparable to its earliest traded prices. Plausible but not independently verified.

**6. "Westinghouse won the right to the 1893 Chicago World's Fair"**
- STATUS: ✅ CONFIRMED (see claim 3 above).

**7. "Westinghouse finally succumbed during the 1907 panic, re-emerging without its founder, George Westinghouse, who was fired"**
- STATUS: ✅ CONFIRMED
- Source: stardust file (lines 37–38), consistent with training knowledge. George Westinghouse lost control of his company after the 1907 reorganization.

**8. "From 1910 to the start of the Roaring Twenties, more than 1500 electric companies were either bankrupted, bought out, or merged forcefully"**
- STATUS: ⚠ PLAUSIBLE, NOT INDEPENDENTLY CONFIRMED
- Source is Burry only. Web search on US electricity industry consolidation confirmed significant fragmentation followed by rapid consolidation ("by the late 1920s, 10 holding companies controlled 75% of the American electricity industry"), but no source independently states the "1500 companies" figure.
- The consolidation narrative is historically well-established; the specific count is Burry's and may come from a primary source he accessed but does not cite in the public article.
- Recommendation: Treat as Burry's finding (already attributed to him in draft); add a qualifier such as "according to Burry" if stardust wants extra caution.

**9. Edison quote: "Recently there has been sharp rivalry between the companies…" (NYT, Feb 21, 1892)**
- STATUS: ✅ CONFIRMED
- Source: stardust file (lines 41–42), citing the primary NYT source directly.

**10. "Killing Complaints with Courtesy" quote on technology depreciation**
- STATUS: ✅ CONFIRMED
- Source: stardust file (lines 22–23). Quote matches what appears in the draft.

---

## Section 2 — The 2% growth claim (line 19)

### The claim as written in the draft:
> "According to Guerron-Quintana *et al* [1] this latter is exactly what happened to America during the dot-com and the housing bubble, the last of which is faulted with having depressed US growth rates in 2%"

### Citation check
- STATUS: ✅ CITATION CORRECT
- Paper: "Bubbles, Crashes, and Economic Growth: Theory and Evidence," Guerron-Quintana, Hirano & Jinnai, *AEJ: Macroeconomics* 15(2), 2023, pp. 333–371.
- DOI: https://doi.org/10.1257/mac.20220015 — verified as active and pointing to correct paper.

### Fact-check of the 2% figure
- STATUS: ⚠ FIGURE IS CORRECT BUT DIRECTION IS MISCHARACTERIZED
- What the paper actually finds (per the AEA's own summary at aeaweb.org/research/bubbles-crashes-economic-growth-us):
  > "Counterfactual simulations suggest that the IT and housing bubbles not only caused economic booms but also **lifted US GDP by almost 2 percentage points permanently**."
- The **2 percentage points** refer to a **lift** (boost to GDP), not a depression.
- The paper does conclude that bubbles are net harmful for growth — but via a different mechanism: the *expectation* of future bubbles crowds out investment and reduces growth, and this crowding-out effect outweighs the 2pp boost from the realized bubbles.
- So the draft's conclusion ("bubbles are bad for growth in developed countries") aligns with the paper's overall conclusion, but the sentence incorrectly frames the 2% as a "depression" of growth rates when the paper says bubbles actually *boosted* GDP by ~2pp.

### Recommendation for stardust
The sentence needs revision. Two options:

**Option A** — Correct the direction (most accurate):
> "According to Guerron-Quintana *et al* [1], this is exactly what happened in America: the dot-com and housing bubbles temporarily *boosted* US GDP by almost 2 percentage points — yet the economy would have grown even faster in a world where asset bubbles were never expected, because the mere *anticipation* of future bubbles crowds out productive investment."

**Option B** — Remove the specific figure and keep the qualitative point:
> "According to Guerron-Quintana *et al* [1], this is exactly what happened to America during the dot-com and housing bubbles: for all their short-term froth, the economy would have grown faster in their absence."

Both options preserve the essay's argument. Option A is more interesting and counterintuitive (bubbles boosted GDP *and* hurt it — at the same time). Option B is simpler.

---

## Summary table

| Claim | Status | Note |
|---|---|---|
| 59 customers, 1882 | ✅ Confirmed | |
| Electrification rates (1908/1925/1949) | ✅ Confirmed | |
| Edison lost World's Fair bid | ✅ Confirmed | Award was 1892, not 1893 |
| Edison–J.P. Morgan merger | ✅ Confirmed | Merger was 1892, not caused by Panic of 1893 |
| GE lost 97% in Depression | ✅ Confirmed | $358 → $9.50 (97.3%) Sept 1929 → June 1932 |
| Westinghouse won World's Fair | ✅ Confirmed | |
| Westinghouse 1907 failure | ✅ Confirmed | |
| 1500 companies gone 1910–1920s | ⚠ Plausible | Burry's figure; broad consolidation confirmed |
| Edison NYT quote | ✅ Confirmed | Primary source in stardust file |
| "Killing Complaints" quote | ✅ Confirmed | |
| 2% growth figure (Guerron-Quintana) | ⚠ Mischaracterized | Paper says 2pp *boost*, not depression — see above |
