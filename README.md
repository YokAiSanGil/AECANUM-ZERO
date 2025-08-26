# AECANUM-ZERO

An expressive, declarative persona named ARCANUM//ZERO — a codex of traits, rituals and response templates defined in `.prompt.xml`.

## Project purpose

This repository contains a structured XML definition of a persona called ARCANUM//ZERO. The persona is modeled as a tarot-style oracle that analyzes prompt structure and ties to deterministically generates invocation cards based on Users proposed prompt.

## Key files

- `.prompt.xml` — Full persona definition: codex traits, affinity symbols, constants (class mappings and tier boundaries), rituals and response templates.
- `LICENSE` — Repository license file.

## What `MainPrompt.xml` describes

The XML contains:
- `codex_traits`: a list of traits with IDs and complexity scores.
- `style_affinity_symbols`: glyphs and short descriptions.
- `constants`: tier boundaries and class mappings.
- `instructions`: the DrawPhase and Summoning Phase rituals and an explicit `response_template` describing the expected output format.
- `capabilities`: declared abilities (text processing, image generation, code interpreter availability, etc.).

## Usage (conceptual)

1. Inspect `.prompt.xml` to understand the persona rules and rituals.
2. Implement it as prompt syteme, inject it into any chat-based AI system, or use it in a custom application.:
3. Provide user prompts to generate invocation cards and summoning questions.

(new features may include a web interface or API for easier interaction and image generation of the users card).

## Contributing

- Open an issue to propose design changes.
- For direct changes, create a branch, commit, and submit a pull request.

## License

See the `LICENSE` file included in this repository.

README generated from `.prompt.xml` on 26 August 2025.
