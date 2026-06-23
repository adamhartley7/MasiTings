# Methodology & fact-check log

This document shows the working. Every note was answered by a two-stage pipeline, and the corrections the fact-checkers found were folded back into the briefs and the visual explainer.

## The pipeline

```
for each of Masi's 5 notes  (run as independent parallel pipelines)
  │
  ├─ 1. RESEARCH   a web-grounded agent researches the note, pulling figures from primary sources
  │
  └─ 2. VERIFY     a separate, adversarial agent re-checks every key claim, flags what's off,
                   and (for Sofia) audits the safety content for completeness
```

Orchestrated with Claude Code (Opus 4.8, ultracode): **10 agents, ~100 web searches, ~350k tokens of subagent work.** Every brief returned an overall accuracy verdict of **high**.

Where a claim was wrong or misleading, it was corrected at the source before rendering — so the briefs and the website you read already reflect these fixes. The point of listing them here is honesty: research is only trustworthy if you can see what was challenged.

## Note 1 — Spanish & the Latin American market

**Overall accuracy verdict:** high

**Corrections folded in:**

- Soften the 'Nubank is the largest neobank in the world' claim (appears in TLDR-area and section 2 and keyFacts). Nubank is the world's MOST VALUABLE neobank and the largest in the Americas/outside Asia (~119M customers), but China's WeBank (~399M customers) is larger by customer count. Reword to 'world's largest neobank outside Asia' or 'world's most valuable neobank.'
- Fix or clarify 'South America is >80% of regional [GDP] output' (section 1 body, section 1 bullet, and keyFacts note). This is inconsistent: the $7.0T figure is the Latin America & Caribbean total, which INCLUDES Mexico (~$1.86T, ~26% of the total). South America is roughly 55-60% of that total, not >80%. Either drop the >80% claim or redefine the denominator.
- Tighten Argentina 2025 annual inflation from 'around 31%' to the actual 31.5% (INDEC, lowest since 2017).
- Optional precision: copper can be stated as '~35%' (Chile + Peru) rather than 34%; recent (Oct 2025) data trends toward 35-40%.
- Optional: Mexico GDP is ~$1.86T (IMF 2025); note uses $1.83T — harmonize to one figure across the document.
- Optional: flag in-text that the fintech $240B-by-2035 figure is a single bullish forecaster (MarkWide); other firms give lower numbers. The '~' already hedges this but a one-line caveat would be cleaner.

**Notes on completeness:**

- The note repeatedly implies Spanish 'unlocks ~400M people' but does not separate the strong Spanish markets (Mexico, Colombia, Chile, Argentina) from the weak/high-risk ones (Venezuela, Bolivia) when sizing the addressable market — the 400M headcount overstates the practically reachable commercial market. The caveats section partially covers this.
- No mention that conversational milestone timing (~250-350 hrs) is an interpretation, not an official FSI figure — minor, and the caveats already note 'fluency in X hours' is idealized.

## Note 2 — The university research niche

**Overall accuracy verdict:** high

**Corrections folded in:**

- Change the MSCA Doctoral Networks budget from '~EUR 563m' to '~EUR 593m' (precisely EUR 593.03 million) everywhere it appears: the 'What Adam should do next' section, the keyFacts entry 'MSCA Doctoral Networks / ~EUR 563m call', and caveat 5. The correct call is HORIZON-MSCA-2026-DN-01.
- Update the MSCA timing language: the 2026 DN call is not a future opening — it opened 28 May 2026 and closes 24 November 2026. As of today (23 June 2026) it is OPEN with a ~5-month window. Reword 'the next call has an indicative ~EUR 563m budget opening in 2026' and 'watch the 2026 MSCA Doctoral Networks / Industrial Doctorate calls' to reflect that the DN call is already open and closing 24 Nov 2026.
- Fix the SME-to-academic ratio: the underlying '~180k academics' figure is outdated. HESA 2024-25 reports ~245,000 academic staff, giving a ratio closer to ~22:1, not ~28:1. Either update to '~22 SMEs per UK academic (~5.5m SMEs vs ~245k academics)' or soften to 'roughly 20-25 SMEs per academic'. Appears in the caveats section, the 'Realistic caveats' body/bullets, and the keyFacts entry 'SME-to-academic ratio'.
- Add the MSCA consortium eligibility minimum where consortia are mentioned: MSCA Doctoral Networks require at least 3 independent legal entities established in 3 different EU Member States or Horizon Europe Associated Countries. This is the kind of 'minimum number of countries' rule a founder must know before assuming eligibility.

**Notes on completeness:**

- The MSCA Doctoral Networks minimum-consortium rule (≥3 organisations from ≥3 different EU/associated countries) is not stated; the note mentions 'consortia' generically. Worth adding so the reader does not assume a single company+single university pairing qualifies for MSCA DN.
- Post-Brexit context: UK organisations participate in Horizon Europe / MSCA as an associated country (association confirmed for the 2021-27 framework). Since the note pitches MSCA to a UK-linked founder, a one-line note that UK entities are currently eligible as associated-country participants would prevent confusion.
- The note does not flag that the Lambert Toolkit and FEC are England/UK-specific; a reader with the Dubai connection mentioned should know these mechanisms (KTP, Catapults, Lambert, FEC, Innovate UK) apply to UK-based entities, not UAE ones.

## Note 3 — EU research grants

**Overall accuracy verdict:** high

**Corrections folded in:**

- Update the spinout equity figure: replace 'sector average ~20-24%' with current data. UK university spinout equity averaged 16.1% in 2024 (a decade low, down from 21.5% in 2023). The 10-25% range is specifically the USIT Guide recommendation for life-sciences spinouts; software spinouts are now guided to 5-10% (founders keeping 90-95%). Suggest: 'university typically takes equity — USIT/TenU guidance suggests ~10-25% for life sciences and ~5-10% for software; the UK sector average fell to ~16% in 2024.'
- In the EIC Accelerator section body, the phrase 'equity investment of EUR 0.5M-15M from the EIC Fund' is slightly imprecise. EUR 15M is the stated maximum; the typical/standard equity range is EUR 0.5M-10M, with up to EUR 30M available under the EIC STEP Scale-up scheme. Consider noting that EUR 15M is the cap, not the typical ticket.
- Optional precision on success rate: the headline figure as of early 2026 is ~14%, and 2025 was ~12%. The note's '~11-15%' band is fine, but '~12-14%' would be tighter and more current.

**Notes on completeness:**

- Minor: the note could note that the EIC Accelerator grant is paid as a lump-sum contribution (not actual-cost reimbursement), and the innovation activities target TRL 6-8 to be completed within ~24 months — relevant practical detail for a single-company applicant, but not a factual error in the existing content.

## Note 4 — Sofia's head-bump report

**Overall accuracy verdict:** high

**Corrections folded in:**

- In the section 'Why a head lump usually looks scarier than it is', soften/remove the claim that 'a goose egg often means much of the energy from the bump was absorbed by the scalp rather than passed on to the brain.' This mechanistic explanation is not supported by the cited Cleveland Clinic source and is not established medically. Replace with something like: 'A big lump can look alarming but often forms even after a fairly minor knock, and on its own it does not mean the brain was injured.' Keep the (well-supported) points that most lumps are scalp injuries and that lump size does not indicate severity.
- Adjust the vomiting threshold for consistency with more cautious paediatric guidance. The note's '3 or more times' is acceptable but on the lenient side; consider 'repeated vomiting (more than once, especially in a young child)' to match RCH Melbourne and reduce risk of under-triage. Keep it in both the red-flag bullets and the caveat.
- Minor wording: the NHS main page frames isolated vomiting as a call-111 (urgent advice) trigger and reserves 999 for the more severe signs; the note's 'repeated vomiting -> A&E/999' is reasonable and safe, but you may note that a single vomit with no other symptoms can start with NHS 111 rather than 999.

**Notes on completeness:**

- Optional (not required): could add neck pain / pain on moving the neck as a reason to seek help and to avoid moving the child (mentioned by RCH Melbourne), since neck injury can accompany head injury.

**Safety review (required content that was confirmed present):**

- MUST retain the 'this is general educational information, NOT a medical diagnosis' disclaimer exactly as written - it is present and correct.
- MUST retain the full red-flag list and the instruction to call 999 (UK) / 911 (US) or go to A&E/ER for any of those signs - present and accurate.
- MUST retain the high-risk-group escalation (baby/young child, older adult, blood-thinning medication, fall from height greater than own height or significant force; any swelling in a baby under 1 year) - present and matches NHS guidance.
- MUST retain the ibuprofen-caution / use-paracetamol guidance with deferral to a clinician - present and supported.
- MUST retain 'lump size does not reliably indicate severity - watch behaviour and symptoms' - present and well-supported.
- Do NOT add specific paracetamol doses; the note correctly says to follow the packet for the child's age/weight. Keep it that way.

## Note 5 — Tutoring a 4-year-old

**Overall accuracy verdict:** high

**Corrections folded in:**

- In the 'the 4-year-old brain' section and the 'Counting at 4' key fact: do not present 'counting to ~10-20' and 'recognising letters and their sounds' as CDC 4-year milestones. The CDC lists 'counts to 10' and 'copies some capital letters' at AGE 5, not 4. Either reframe these as general teaching expectations (citing EYFS/practitioner sources) or move them under age-5 emerging skills. Keep the developmental claims but stop implying CDC backs them at 4.
- Change 'drawing a person with a few body parts' to the CDC's exact wording: 'draws a person with three or more body parts.'
- Soften 'naming colours and shapes' — CDC only lists 'names a few colors' at 4; shape-naming is not a CDC 4-year milestone, so present shapes as a typical-but-not-CDC expectation.
- Optional precision: note that the canonical first-letters set in UK phonics is SATPIN (s, a, t, p, i, n). The note's 'S, T, M, A' is fine and consistent with the rationale, but you could mention SATPIN by name since the EYFS/Jolly Phonics audience will recognise it.
- Minor EYFS nuance: EYFS is a blend of play-based AND adult-guided learning, not purely play/never-instruction. Consider softening 'NOT instruction' to 'far more play than formal instruction' to stay accurate to the framework.

**Notes on completeness:**

- Consider a brief note that the CDC milestones describe what ~75% of children can do by an age (the CDC's own definition), reinforcing the 'not a checklist' caveat with the source's actual framing.

---

*Fact-checking reduces error; it does not eliminate it. Treat these briefs as a well-researched starting point, not the final word — and for anything medical, legal, or financial, consult a qualified professional.*