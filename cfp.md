---
layout: default
title: Call for Papers
---

# Call for Papers

## AI Foundations for Power Grids: From Models to Deployment at Scale
### A NeurIPS 2026 Workshop

**Tagline.** *What would it take for AI models to enter a power grid control room? A workshop on benchmarks, model training, and real-world considerations.*

**Date & venue.** December 11 or 12, 2026 — co-located with NeurIPS 2026 in **Sydney, Australia**. In person.

**Website.** [workshop URL TBD]\
**OpenReview.** [OpenReview venue URL TBD]

---

## Scope

The power grid is one of the most consequential open problems in applied machine learning — hard physics constraints, real-time closed-loop operation, structural non-stationarity, and societal-scale consequence — yet it attracts a fraction of the methodological attention given to vision, language, or biology. This workshop brings power systems to the ML community as a first-class methodological challenge and focuses on the central bottleneck: **how to evaluate learning-based methods under realistic and evolving operating conditions.**

Themes we especially welcome:

- **Open, realistic datasets** as a first-class community deliverable, beyond legacy IEEE test cases.
- **Feasibility as a metric** — what it means for a stochastic model to "respect the physics", beyond aggregate error.
- **Structural, not just sample, shift** — real grids change topology hourly and generation mix yearly.
- **Foundation-model claims for grids** and the criteria by which to evaluate them.
- **Components vs. systems** — a 99% accurate surrogate can destabilise the loop it sits inside.
- **From eyes-on to eyes-off** — offline, advisory, and narrow-autonomy stages each demand different evidence.

## Submission tracks

Authors select one primary track at submission:

1. **Methods with rigorous evaluation** — new models evaluated beyond in-distribution error on a static test case.
2. **Benchmarks, datasets, and evaluation protocols** — contributions whose primary artifact is *how* we measure.
3. **Position and empirical-evaluation papers** — systematic studies, audits, or arguments about what good evaluation should look like.
4. **Negative results and failure modes** — short papers documenting where learned components break, especially under structural or distributional shift.

## Evaluation checklist

Submissions must include a short **domain checklist** at the end of the paper (outside the 4-page limit). For each item, state where it is addressed or justify "not applicable":

1. **Physics feasibility.** For methods producing grid quantities: is feasibility reported under the full **AC** power-flow equations, not only the linearised **DC** approximation? Include constraint-violation statistics, not just aggregate error.
2. **Out-of-distribution evaluation.** Is the method evaluated on at least one network topology, generation mix, or operating regime not seen in training?
3. **Failure modes.** Are failure cases reported alongside aggregate metrics — worst-case behaviour, tail statistics, or qualitative examples?
4. **System-level effect** (where applicable). For components inside a larger system, is the downstream effect reported, not only standalone accuracy?
5. **Data and code.** Will code and data be made available (anonymously at submission, or on acceptance)? A clear release plan is sufficient.

Reviewers score on standard NeurIPS criteria (novelty, technical quality, clarity, significance) **and** on how substantively the paper engages the checklist.

## Format & submission

- **Length:** up to **4 pages** of main content, unlimited references. Appendices are permitted but reviewers are not obligated to read beyond the main text. Use the NeurIPS 2026 workshop template.
- **Anonymization:** double-blind; anonymize author identity in the paper, supplementary material, and any code/data links.
- **Track selection:** authors select one **primary track** at submission via the OpenReview form.
- **Portal:** all submissions via **OpenReview** (link above).
- **Reviews:** each paper receives **3 double-blind reviews**.
- **LLM policy:** authors must disclose any use of LLMs in preparing the submission; fabricated or hallucinated content is grounds for desk rejection. Reviewers may not use LLMs to write reviews.

## Key dates (all AoE)

| Milestone | Date |
|---|---|
| Submission deadline | **August 29, 2026** |
| Author notification | **September 29, 2026** (mandatory NeurIPS deadline) |
| Workshop date | December 11 or 12, 2026 (Sydney) |

## Eligibility

- Original work not previously published at an ML venue. Prior appearance in a **power-systems venue** (journal or conference) is acceptable provided this is **explicitly disclosed** and the paper offers new value to an ML audience.
- Work in progress, position papers, and negative results are welcome.
- **Not eligible:** work already published (or accepted, or presented) at NeurIPS, ICML, ICLR, AAAI, or comparable ML venues; work appearing at the NeurIPS 2026 main track; papers outside scope.

## Archival status

**Non-archival** — no formal proceedings. Accepted papers may be posted publicly on OpenReview at the organizers' discretion; authors retain copyright and the right to submit extended versions elsewhere. Per NeurIPS policy, work presented here may later be submitted to a future NeurIPS main track only if **substantially extended**.

## Presentation

Contributed talks (15 min), lightning talks (5 min), and a poster session with all accepted papers.

## Conflicts of interest

**Organizers may not submit.** Authors with a personal COI (advisor/advisee, close collaborator, or same institution as any organizer) may not submit. Reviewers recuse on COI; submissions involving organizer-maintained benchmarks are routed to a disjoint PC subset.

## Diversity and inclusion

We encourage submissions from authors of all backgrounds, career stages, institution types, and geographies, and particularly welcome contributions from the power-systems community engaging ML as a methodological challenge.

## Contact

Questions: <ai4powergrids@gmail.com>

**Organizers:** Andrea Britto Mattos Lima (Microsoft Research), Baosen Zhang (University of Washington), Wenqi Cui (NYU), Thomas Brunschwiler (IBM Research), Nicolas Christianson (Johns Hopkins University), Rabab Haider (University of Michigan), Christopher Yeh (Caltech / Harvard).
