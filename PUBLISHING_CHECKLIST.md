# Publishing Checklist

Use this checklist before anything in this repository becomes public.

## Content Red Flags
- Remove any real private folder, file, service, model, controller, repository, provider, event, feature key, or script name.
- Remove any explanation that reveals how progression generation, suggestions, ranking, monetization, or analytics actually work.
- Remove any sentence that reads like internal documentation rather than a curated public artifact.
- Remove implementation sequences such as "first we built X, then we added Y."
- Remove architecture detail that helps map the real codebase.

## Tone Check
- Keep the writing calm, precise, and confident.
- Remove hype, jargon, and academic phrasing.
- Simplify any sentence that sounds like it is trying too hard to impress.
- Prefer fewer, stronger claims over broad coverage.

## Screenshot Review
- Use happy-path screens only.
- Remove debug text, internal labels, edge states, and future-facing surfaces.
- Crop aggressively.
- Blur incidental text if it reveals too much.
- Avoid screenshots that expose premium mechanics, analytics hints, or hidden product language.

## Diagram Review
- Describe capabilities, not systems.
- Keep diagrams small and conceptual.
- Avoid boundaries, component maps, technical labels, and data flow.
- Delete any diagram that starts to feel reconstructable.

## Code Review
- Prefer no code at all.
- If code is included, it must be generic, short, and rewritten from scratch.
- Do not publish domain-specific logic or anything close to production structure.
- If a snippet could be expanded by an AI agent into a useful product foundation, do not publish it.

## Business And Strategy Review
- Do not publish event taxonomies, funnel details, conversion logic, or monetization triggers.
- Describe premium only at the user-value level.
- Avoid revealing internal priorities, future moat-building mechanics, or growth playbooks.

## Final Question
If a smart competitor spent one hour with this repository, would they leave with a meaningful head start on cloning GuitarGuide?

If the answer is yes, cut more.
