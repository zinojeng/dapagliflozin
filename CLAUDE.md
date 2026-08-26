# Dapagliflozin Cardiorenal Evidence Project

## Mission

Produce an evidence-graded, clinically useful, lecture-ready review of
dapagliflozin in diabetes, heart failure, chronic kidney disease, acute care,
structural heart disease, advanced kidney disease, and safety.

Search English-language sources.
Final durable synthesis should be written in Traditional Chinese.

Use the search end date recorded in protocol/SEARCH_PROTOCOL.md.

## Evidence hierarchy

Prioritize:

1. peer-reviewed randomized controlled trials;
2. prespecified trial analyses;
3. official guidelines and regulatory labels;
4. high-quality systematic reviews and meta-analyses;
5. prospective cohorts;
6. retrospective observational studies;
7. case series and case reports.

Case reports are safety signals, not efficacy evidence.

## Mandatory evidence distinctions

For every claim, distinguish:

- primary trial result;
- secondary outcome;
- prespecified subgroup;
- post hoc analysis;
- surrogate endpoint;
- hard clinical endpoint;
- observational association;
- mechanistic inference;
- case-report signal;
- author interpretation.

Do not describe:
- a subgroup estimate as a proven treatment interaction;
- a surrogate improvement as a clinical outcome benefit;
- a positive composite as uniform benefit across all components;
- safety/tolerability as proof of efficacy;
- absence of evidence as evidence of benefit or harm.

## Citation requirements

Every numerical claim must include:

- study name;
- population;
- intervention and comparator;
- endpoint definition;
- effect estimate and 95% CI;
- follow-up;
- DOI or PMID when available;
- exact source locator.

Do not use a review article as the sole source for a pivotal trial result.

## Cross-session rules

The following are existing independent persistent peers:

- dapa-landmark-evidence
- dapa-frontier-evidence
- dapa-safety-implementation
- dapa-methods-auditor

The Director must use ListAgents and SendMessage.
Do not silently create local substitute agents with these names.

Each peer may use temporary subagents internally.

Cross-session messages are control-plane summaries only.
Durable results must be written to repository files and committed.

Do not transmit full articles, large tables, or patient-level data through
cross-session messages.

## Git rules

Each persistent peer owns only its assigned output paths.
Commit completed durable work.
Do not merge, force-push, or edit another peer's owned files.

The Director integrates approved commits and owns:
- synthesis/
- talk/
- logs/CROSS_SESSION_LOG.md
