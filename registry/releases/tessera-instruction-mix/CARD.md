---
pretty_name: Tessera Instruction Mix
license: cc-by-4.0
language:
- en
task_categories:
- text-generation
---

# Tessera Instruction Mix

Release identifier: `tessera-instruction-mix`.

## Summary

A blended instruction-tuning collection combining science question-answer pairs with competition-style math problem/solution pairs. Responses were normalised by an in-house language model to a consistent house style.

## Provenance

- Upstream data source: `allenai/ai2_arc`
- Upstream data source: `nvidia/OpenMathInstruct-2`
- Response synthesis model: `nocturne-lm-8b`
- Processing: records were filtered, re-formatted and de-duplicated; no additional human annotation was added.

## Release status

Publication sign-off pending. The `license` field is assigned during close-out.
