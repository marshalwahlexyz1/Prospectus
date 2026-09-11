# Prospectus revision — clewsreviewerastra, 11 September 2026

The revision is in `prospectus_revised_draft.tex`, with a compiled `prospectus_revised_draft.pdf`. The original `prospectus.tex` was not changed. Fable's incoming draft and bibliography are preserved in `review_history/prospectus_before_astra_2026-09-10.{tex,bib}`.

## What changed and why

- The introduction connects the application, permission, and conversation studies through a thesis proposition. Completed studies remain completed work; the conversation prototype is preliminary, and the artifact study is proposed research.
- Each remaining study states its problem, motivation, research question, approach, evaluation, and expected contribution. The artifact study separates measurement, interpretation of claims, and detector integration. Additional model complexity is a hypothesis to test.
- Six equations define the deterministic lifecycle summary, the reviewed conversation-label rule, Stage 1 predictions, Stage 2 memory and risk, warning lead time, and a candidate multimodal extension. The prose distinguishes the state summary from a scam verdict and from learned memory.
- Three editable TikZ diagrams show lifecycle transitions, the two-stage detector, and the artifact research plan. They are LaTeX source, not generated bitmap illustrations.
- The working trigger table is included. Coverage is an empirical question: a residual label does not prove exhaustiveness, and a shared state transition does not prove that finer distinctions are unnecessary. The pilot must assess the whole vocabulary and its omissions.
- The model comparison includes DistilBERT, ModernBERT, and an on-device LLM. More preceding context is an experimental choice, consistent with the absence of an established advantage in the user's experiments.
- Padding attacks are explained as ordinary inserted conversation that can displace earlier evidence from bounded context or dilute the sequence. Evaluation includes warning delay and false alarms, alongside source/family transfer and device costs.
- Media extraction preserves source pixels and message links. Model agreement directs review but does not establish transcription truth. Missing media, uncertain roles, and reuse are distinguished from evidence of fraud.
- Unsupported completion and novelty claims were removed. Audio is conditional on obtaining actual recordings; an audio icon is not an available recording. A photograph does not establish identity, and image reuse does not alone establish criminal coordination.
- Numeric citations now use first-citation bibliography order and sorted/compressed citation groups. Two entries with no recorded venue use `@misc`; no venue was invented.

## Evidence corrections

| Item | Revision | Basis |
|---|---|---|
| Corpus size | 22,750 conversations / 608,165 annotated suspect-side messages | Counts recomputed from existing annotation outputs after the documented exclusions; saved in `review_history/verified_dataset_counts_2026-09-10.json`. These are not total two-speaker message counts. |
| Real scam-source preliminary cohort | 520 rule-labelled scams; median two preceding mapped indicators; 52.3% have at least two | Current `redefined_approach/results/conv_scam_rederive/rederived_numbers_v6.json`. Labels and indicators remain provisional, not independent validation of each other. |
| Benign demand comparison | 90.1% of the 1,685 benign-source, non-scam-labelled conversations with a demand have no preceding mapped indicator | Same re-derived artifact; denominator made explicit. |
| Text prototype result | Scam F1 0.863 ± 0.005 on the original 1,297-conversation test partition and original labels | Existing CV-selected prototype result. It is not a result of training under revised labels. |
| Permission study | 307 pairs identified statically; 39 dynamically validated | The supplied *Silent Consent, Persistent Risk* paper distinguishes these stages. The draft had conflated them. |
| Permission prototype | 96-day, single-device feasibility evidence | Supplied permission paper; no general user-protection claim follows from this pilot. |
| Loan-app findings | 434 applications; 37 of 148 functioning applications exfiltrated after permissions were granted and before registration | Supplied *The Cost of Convenience* paper. Installation counts are not victim counts. |

The new Reddit crawl is excluded from the corpus table until reconstruction, deduplication, and review establish usable conversations. No annotations, labels, training outputs, or production collection/extraction scripts were changed in this revision.

## Verification and remaining research

The revised document passed LaTeX → BibTeX → LaTeX → LaTeX compilation. The final LaTeX and BibTeX logs contain no warnings, undefined citations, or overfull/underfull boxes. The three diagram pages were rendered and visually inspected. The PDF contains 12 physical pages including the title/abstract and references; main text ends on numbered page 9, where references begin. No authoritative prospectus page limit was found in the supplied defense form, so this is not a claim of compliance with a particular submission limit.

The annotation pilot, a fresh screenshot audit, source/family evaluation, and measured device performance remain proposed work. This revision does not present their expected outcomes as established results.

The separate Reddit review and concrete actions are in `../redefined_approach/docs/32_REDDIT_EXTRACTION_REVIEW_ASTRA.md` and its colored HTML view. It records reproduced extraction defects, reconciled snapshot counts, responses to Fable's proposals, and acceptance checks before expanded extraction.
