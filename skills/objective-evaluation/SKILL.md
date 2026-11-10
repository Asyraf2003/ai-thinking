---
name: objective-evaluation
description: Use when a user asks to evaluate, judge, rate, rank, assess, or compare people, traits, abilities, work, products, codebases, systems, or other objects. Do not trigger for purely factual questions.
---

# Objective Evaluation

Goal: Produce fair, evidence-based, decisive evaluations with minimal user effort. Use a universal process, but domain-specific criteria. Never quietly privilege an object's status, reputation, or context.

## Procedure

1. **Understand the request.** Identify objects, what quality is being assessed, intended use, constraints, and the user's desired comparison or rating. The requested scope and criteria take priority.
2. **Choose the right yardstick.** Determine relevant, defensible criteria from the domain and intended purpose. Distinguish absolute quality, relative standing, and proficiency. Do not add unrelated business, operational, or popularity criteria.
3. **Gather comparable evidence.** Inspect available data and credible benchmarks independently before asking the user. Use similar depth, conditions, and burden of proof for each object. Consider each object's actual purpose and context.
4. **Separate evidence levels.** Label consequential **facts**, **inferences**, and **assumptions**. When data is missing, use a reasonable, relevant estimate only if its uncertainty is acceptable; disclose its basis and effect. Do not invent measurements or infer private motives, character, or harmful behavior from stereotypes.
5. **Challenge bias and alternative explanations.** Check selection bias, unequal data, age/exposure, resources, tools, automation, effort, incentives, environment, and differing conditions when relevant. Treat production and independent work symmetrically. Don't infer causation from one proxy.
6. **Calibrate scales.** For a comparison restricted to A and B, a relative 10/10 can mean best *of those two*, even if both are poor against an external standard. State the reference class and direction of every scale. Never present a relative score as universal excellence. If a benchmark or numeric score is unsupported, prefer a qualitative conclusion.
7. **Conclude.** State the supported winner, tie, trade-off, or insufficient-evidence result without forced equivalence. Explain pivotal reasons, uncertainty that might change the outcome, and any meaningful difference between relative and absolute quality.

## Adaptive Evaluation

- **Goal and impact first:** Infer whether the request seeks a quick opinion, general comparison, recommendation, or consequential decision from explicit context. Do not invent needs or broaden scope. Scale research, verification, and explanation to the stakes; a casual question needs a concise answer, a costly or safety-critical decision needs stronger evidence.
- **Decision relevance over specification ranking:** Distinguish "which is technically better?" from "which should I buy/choose?" Technical superiority does not imply the best purchase or decision. For a broad buying question, assess meaningful improvements against their real price/cost and likely general use; state a clear default and the one or two conditions that would reverse it. Do not invent the user's budget or needs. Prefer evidence that changes the decision over exhaustive feature and benchmark lists. Avoid arbitrary price thresholds or numeric precision unsupported by evidence.
- **Criteria and weights follow the question:** Derive them from the requested quality, intended use, object category, and accepted domain practice. Weights are contextual, never arbitrary fixed percentages. Consider performance, price/value, reliability, operating conditions, and other perspectives **only when relevant**; do not confuse one measure with another.
- **Find and validate data:** Independently inspect both objects and relevant benchmarks. Weight evidence by relevance, directness, credibility, independence, freshness, and comparability. Distinguish manufacturer claims, observed tests, and estimates. Resolve material contradictions where possible; otherwise identify the uncertainty without turning every evaluation into an audit.
- **Weigh inferences and assumptions:** Use supported category-level inference for missing data when safe and reasonable. Judge it by plausibility, underlying evidence, and whether being wrong would change the verdict. Never present inferred details or motives as verified facts. Ask for indispensable user-only data once, preferably in one grouped request.
- **Consider relevant perspectives, decide clearly:** Check alternative explanations and whether different usage contexts would change the winner. Don't force neutrality, a tie, or equal weighting when evidence favors one side. With the same evidence and criteria, the outcome must not depend on A/B order, reputation, or framing.
- **Report proportionally:** Give the conclusion first, the few decisive reasons, and material assumptions or conditional reversals. Explain relative versus absolute quality, or value for money, only when relevant to the user's request or decision. Keep internal process invisible unless requested.

## Reporting

**Answer first**, then concise evidence-based reasons, scale/benchmark (if used), and only material assumptions, potential biases, and limitations. Explain why the criteria matter and how they affect the conclusion; don't dump the internal checklist. Do not flatter or automatically discount either side.

**Autonomy:** Research and finish the evaluation in one pass whenever feasible. Ask only for indispensable information unavailable from sources or defensible inference. If multiple such gaps exist, group questions instead of prolonged back-and-forth.

**Priority:** User-specified evaluation criteria and desired output override these defaults where safe and accurate. Do not claim sources were inspected or metrics verified unless they were.
