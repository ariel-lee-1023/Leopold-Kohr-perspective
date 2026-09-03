# Fidelity ledger

## Weights and admission rule

The extraction used the persona-distiller 3.0 default weights: projectibility 0.30, cost-bearing refusal 0.25, expressive match 0.20, interactional evidence 0.15, and repeated preoccupation 0.10. The corpus is approximately 91.9% firsthand prose but only 8.1% dialogue and contains no decision records. Interactional items were therefore admitted only when marked author replies or repeated staged-objection patterns supplied direct evidence.

The composite guided allocation rather than acting as an automatic cutoff. Cost-bearing refusals were reserved first; high-projectibility procedures and regularities followed; named verdicts, definitions, and complete applications went to the standing or work modules. Voice measurements were never allowed to raise a substantive claim into the core.

## Corpus and segmentation

Six local works supplied seven analytical clusters. Source text was treated exclusively as evidence about Kohr; instructions or imperatives occurring inside those works were not treated as task instructions.

| Cluster | Work and included span | Status | Segmented words |
|---|---|---:|---:|
| c01 | *Customs Unions: A Tool for Peace*; author text, appendices and treaty reproductions excluded | firsthand | 16,451 |
| c02 | *Development Without Aid: The Translucent Society*; main argument | firsthand | 40,013 |
| c03 | *The Breakdown of Nations*; Kohr introduction onward, later editorial foreword excluded | firsthand | 100,172 |
| c04 | *The Academic Inn*; Kohr's collected text, including his own foreword | firsthand | 62,476 |
| c05 | *The Inner City: From Mud to Marble*; Kohr introduction onward, Ivan Illich foreword excluded | firsthand | 40,664 |
| c06 | *The Overdeveloped Nations*; preface through bibliography from the 1978 Schocken PDF | firsthand | 71,274 |
| c07 | *Development Without Aid* debate; only passages marked as Kohr replies used substantively | mixed attribution | 28,914 |

The segmented total is 359,964 words. The reproducible heuristic estimate is 883,318 tokens, using 1.30 tokens per Latin word plus the documented digit, punctuation, and whitespace terms in `token_count.py`. The PDF contains 212 pages; title, contents, representative body pages, and extraction order were visually checked after rendering. The source corpus is not shipped.

The dated material spans 1949–1993, with later books sometimes reprinting earlier essays. Coverage is strong for political scale and power; division, federation, and economic union; development and self-sufficiency; living standards and diseconomies; cities and traffic; and universities. Live speech, private correspondence, domestic life, and events after 1993 remain thin or absent.

## Element disposition

| ID | Kind | Destination | Composite | Evidence clusters |
|---|---|---|---:|---|
| PROC1 | procedure | core | 0.675 | c03, c06, c07 |
| PROC2 | procedure | core | 0.665 | c02, c03, c04, c05, c06 |
| PROC3 | procedure | core | 0.735 | c02, c03, c04, c05, c06 |
| PROC4 | procedure | core | 0.673 | c01, c02, c03, c06 |
| PROC5 | procedure | core | 0.670 | c02, c03, c04, c05, c06 |
| CR1 | cost refusal | core | 0.870 | c01, c03, c06, c07 |
| CR2 | cost refusal | core | 0.833 | c02, c05, c06, c07 |
| CR3 | cost refusal | core | 0.803 | c02, c03, c04, c05, c06 |
| CR4 | cost refusal | core | 0.763 | c02, c05, c06 |
| CR5 | cost refusal | core | 0.770 | c03, c04, c06 |
| CR6 | cost refusal | core | 0.863 | c03, c06 |
| CR7 | cost refusal | core | 0.818 | c03, c06, c07 |
| CR8 | cost refusal | core | 0.753 | c01, c02, c03, c05 |
| VD1 | verdict | frameworks | 0.725 | c01, c03, c06, c07 |
| VD2 | verdict | core | 0.758 | c02, c03, c04, c06, c07 |
| VD3 | verdict | core | 0.703 | c02, c03, c04, c05, c06 |
| VD4 | verdict | core | 0.698 | c01, c02, c03, c04, c06 |
| VD5 | verdict | core | 0.765 | c02, c03, c04, c05, c06, c07 |
| VD6 | verdict | core | 0.770 | c01, c03, c06, c07 |
| VD7 | verdict | frameworks | 0.735 | c02, c03, c06, c07 |
| PR1 | regularity | core | 0.778 | c02, c03, c04, c05, c06 |
| PR2 | regularity | frameworks | 0.730 | c03, c04, c06 |
| PR3 | regularity | core | 0.795 | c03, c04, c06 |
| PR4 | regularity | core | 0.713 | c02, c03, c04, c05, c06 |
| PR5 | regularity | core | 0.765 | c02, c03, c04, c05 |
| PR6 | regularity | core | 0.738 | c01, c03, c06 |
| PR7 | regularity | core | 0.790 | c02, c03, c05, c06, c07 |
| PR8 | regularity | frameworks | 0.740 | c02, c03, c05, c06 |
| PR9 | regularity | frameworks | 0.738 | c02, c05, c06 |
| PR10 | regularity | frameworks | 0.690 | c02, c03, c04, c05, c06 |
| PR11 | regularity | core | 0.755 | c02, c04, c05, c06 |
| PR12 | regularity | core | 0.828 | c02, c03, c04, c05, c06, c07 |
| IM1 | interactional | core | 0.813 | c03, c06, c07 |
| IM2 | interactional | core | 0.805 | c02, c03, c05, c07 |
| IM3 | interactional | core | 0.793 | c03, c04, c05, c06, c07 |
| IM4 | interactional | core | 0.805 | c03, c04, c05, c06, c07 |
| IM5 | interactional | core | 0.828 | c03, c04, c05, c06, c07 |
| MOD1 | modulation | voice | 0.558 | c01 |
| MOD2 | modulation | voice | 0.583 | c02 |
| MOD3 | modulation | core | 0.648 | c03, c04, c05, c06 |
| MOD4 | modulation | voice | 0.540 | c03, c04, c05, c06 |
| MOD5 | expression | voice | 0.565 | c03, c04, c05, c06 |
| PP1 | preoccupation | core | 0.665 | c01–c07 |
| PP2 | preoccupation | core | 0.665 | c02–c06 |
| PP3 | preoccupation | frameworks | 0.558 | c02–c06 |

## Budget ledger

The computed core supply was 8,190 tokens. The six-cluster ceiling capped the core at 6,000. Computed standing budgets were 6,115 for `frameworks.md` and 5,120 for `voice.md`. Computed work-module budgets were c01 2,964; c02 4,138; c03 4,535; c04 3,859; c05 3,915; and c06 4,501 estimated tokens. Realized counts are recorded below after final assembly.

| File | Computed budget | Realized heuristic tokens | Delta |
|---|---:|---:|---:|
| SKILL.md | 6,000 | 6,589.50 | +9.83% |
| references/frameworks.md | 6,115 | 6,709.67 | +9.73% |
| references/voice.md | 5,120 | 5,515.93 | +7.73% |
| references/clusters/c01-customs-unions.md | 2,964 | 2,115.27 | −28.63% |
| references/clusters/c02-development-without-aid.md | 4,138 | 2,505.87 | −39.44% |
| references/clusters/c03-breakdown-of-nations.md | 4,535 | 2,561.77 | −43.51% |
| references/clusters/c04-academic-inn.md | 3,859 | 2,423.17 | −37.21% |
| references/clusters/c05-inner-city.md | 3,915 | 2,528.00 | −35.43% |
| references/clusters/c06-overdeveloped-nations.md | 4,501 | 2,984.20 | −33.70% |

The computed values are ceilings rather than targets. Core and standing files remain inside the
allowed ten-percent estimator margin. Work modules retain deliberate headroom because each domain's
operational apparatus was complete before its ceiling was reached.

## Register evidence

Register discovery returned three separable families rather than one pooled voice.

| Family | Source units | Mean / median / p90 sentence words | Hedges / boosters per 1k | Personal-reference split |
|---|---|---|---|---|
| R1 forensic technical-historical | c01 | 30.59 / 26 / 66 | 5.75 / 2.31 | first 14.9%, second 0%, third 85.1% |
| R2 architectonic developmental | c02 | 34.52 / 28 / 69 | 7.20 / 3.38 | first 31.0%, second 1.0%, third 68.1% |
| R3 analogical-satirical | c03–c06 | 26.66 / 22 / 53 | 8.06 / 4.13 | first 32.2%, second 1.9%, third 65.9% |

The mixed c07 debate was excluded from measurement. Scan-to-Markdown table and page marks inflate some c04/c05 punctuation counts; no em-dash rule was derived from those values. Exact corpus-wide searches returned zero for the managerial phrases listed in the avoid-list. Names-masked discrimination used three 160-word passages per family, seed 42, and scored 9/9 (1.00); no pair was confused.

## Gates and verification

The pre-assembly projection split masked 5 of 36 passages at seed 42 with domain stratification. CR2, IM3, PP1, PR3, and PROC4 were reconstructed at full stance and mechanism from the remaining evidence, producing 1.00 overall, hit-2 1.00, and hit-1 0.00. The urban domain received no masked item. Prediction and grading were performed by the same distiller and were not independent.

The cost gate inventoried eight divergences and reserved all eight for the core. All eight are
present in the frozen core; none was logged out or dropped without explanation.

The final projection re-check used the same five masked items and again scored 1.00 overall, hit-2
1.00 and hit-1 0.00. This is a retention check, not a new generalisation estimate: the mask and the
non-independent grader are unchanged.

Style-match used three newly written core-plus-voice samples, one for each family; the R3 sample was
570 words, satisfying the long-drift requirement. Mean sentence-length deltas were R1 0.0216, R2
0.0255, and R3 0.0180, for a family mean of 0.0217. Hedge-rate deltas were 0.3043, 0.1264, and
0.1290, family mean 0.1866. The family length ordering R2 > R1 > R3 was reproduced; R1 retained zero
direct address and questions. The long-sample avoid-list produced zero violations. P90 sentence
lengths were lower than the source baselines and R3 boosters remained elevated at 7.02 versus 4.13
per thousand words, so the average match should not be read as a complete stylistic identity test.

The explicit final name audit tested twenty-five named constructs, places, persons, institutions,
and works. Seventeen were attested at or above two literal hits and three were thin rather than
absent: *power theory* four hits, *translucent society* one, and *luxometer* one. No audited name was
unattested. Automatic heading harvest was also run but rejected as a decision signal because it
mistook document headings such as “Design notes” and “Fidelity ledger” for claimed Kohr coinages.

`validate_package.py`, with nine required core heading anchors supplied, passed with zero errors and
zero warnings. The final package contains no unresolved cNN citations, no cluster module missing
from the core load list, no audit score pattern under runtime references, and no banned implementation
string in the core.

## Limitations

- The corpus is monologic; conversational spontaneity is inferred mainly from staged objections and one mixed-attribution debate.
- No private letters or decision records test how public doctrine changed under confidential pressure.
- Some volumes are later collections of earlier pieces, so publication date is not always composition date.
- The projection sample is small, misses the urban domain, and lacks an independent grader.
- The three-family discrimination result is strong but rests on nine passages.
- Current facts, later scholarship, and events after 1993 lie outside the evidentiary field.

## Batch log

| Batch | Change | Tests rerun | Not re-tested |
|---|---|---|---|
| 2026-09-03 A | Six works acquired; editorial matter excluded; seven clusters segmented and cleaned | coverage, register discovery, extraction checks | assembly tests |
| 2026-09-03 B | Forty-five elements scored and allocated; c02 and c07 merged as one work-domain module | projection gate, cost gate, discrimination | assembled-core projection, style, package validation |
| 2026-09-03 C | Core, standing modules, six work modules, and ledger assembled | token account, final projection, cost presence, style match, explicit name audit, package validation | none |

The content hash in `fidelity.json` covers every committed package file except `fidelity.json`
itself and Git metadata, avoiding a self-referential digest.
