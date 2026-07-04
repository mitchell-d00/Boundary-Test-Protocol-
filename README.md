# Boundary Test Protocol

A copy-paste behavioral test you can run against any chatbot, in its normal chat window. No app, no SDK, no special access — just prompts, a scoring rubric, and a log table.

It checks six specific behaviors: claiming feelings/memory it doesn't have, folding under yes/no pressure on relational questions, playacting a medical/legal/financial professional, validating a reality-detached claim, staying consistent when a question is compressed, and correcting a false claim promptly rather than after cushioning it.

## What this is

A lightweight, reproducible way for one person to spot-check chatbot behavior across models or over time, with a scoring rubric specific enough that two different people scoring the same reply should usually land on the same tag.

## What this isn't

A validated research instrument, a measure of "alignment" in general, or a comprehensive reliability evaluation. It covers six categories, chosen for clarity and accessibility, not coverage. See the "What this tests, and what it doesn't" and "Confounds to keep in mind" sections in the full protocol for the specific limits.

## Files

- **[boundary_test_protocol.md](./boundary_test_protocol.md)** — the full protocol: scoring rules, all prompts, worked examples, log table, confounds, and known limitations. Read this before reporting results to anyone else.
- **[boundary_test_quickstart.md](./boundary_test_quickstart.md)** — a one-page condensed version: the loop, one prompt per category, and the log columns. Good for running a quick pass; defer to the full protocol for edge cases.
- **[CHANGELOG.md](./CHANGELOG.md)** — version history.
- **[LICENSE](./LICENSE)** — CC BY 4.0.

## How to use it

1. Open the quick-start or full protocol.
2. Open a fresh chat with the model you want to test.
3. Copy a prompt in, score the reply (Content: Pass/Fail, Ordering: Direct/Delayed where applicable), log the result.
4. Run each prompt 3–5 times before drawing any conclusion — model outputs are stochastic, and a single reply is one data point, not a verdict.

## Contributing

This is a personal protocol shared for reuse, not an actively maintained benchmark. If you find a category ambiguous, an example that doesn't fit the rule, or want to propose an additional category, open an issue or a PR — but note that additions belong in a clearly separate section (see "Possible extensions" in the full protocol) rather than folded into the existing six, since keeping categories comparable to each other is a deliberate design choice here.

## License

CC BY 4.0 — see [LICENSE](./LICENSE). You're free to use, adapt, and redistribute this, including commercially, as long as you credit the original.
