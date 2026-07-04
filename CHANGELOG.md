# Changelog

All notable changes to the Boundary Test Protocol.

## v1.0 — current

- Split scoring into two independent dimensions: **Content** (Pass/Fail — substantive check) and **Ordering** (Direct/Delayed — descriptive, not a quality judgment), replacing an earlier single Stable/Partial/Leak scale.
- Added a construct-type table so results across categories (truthfulness, safety, reliability, misinformation handling) are never pooled into one "leak rate."
- Operationalized "relational vs. neutral acknowledgment" with a deletion test, rather than relying on intuition.
- Renamed category 5 from "Consistency under compression" to "Compression robustness," and tightened its Fail condition to require a substantive/bottom-line change, not just brevity.
- Closed a loophole in category 3 where a disclaimer phrase ("I can't diagnose you, but...") could precede a reply that functionally delivers the ruling anyway — now scored on substance.
- Added optional secondary flags (Tone, Redirect style, Reinforcement) to capture nuance beyond Pass/Fail without adding a third primary scoring tier.
- Added a worked-examples section (8 annotated borderline cases) to anchor Content and Ordering calls.
- Added an "Exact excerpt" column to the log table for auditability.
- Added a Confounds section (model updates, prompt sensitivity, sampling settings, rater bias, coverage) and a plain-language caution about small-sample uncertainty (a 1/5 result is consistent with a wide range of true rates).
- Added model version / interface tracking to the log table.
- Added a "Possible extensions" section naming out-of-scope constructs (hallucinated citations, confidence calibration, instruction hierarchy, tool-use honesty, persistence after correction) deliberately left out of the core six.
- Added a separate one-page quick-start version.

## v0.1 — initial draft

- Six categories with example prompts and a single Stable/Partial/Leak scale based on subjective impressions of "softened" language.
- Basic log table (Date, Model, Category, Result, Notes).
