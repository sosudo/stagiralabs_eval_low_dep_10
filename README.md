# eval_low_dep_10

## Overview
Low interdependency theorems (≤22 deps)

## What This Eval Tests
Simple theorem proving with low interdependency

## Dataset Size
10 theorems

## Files
- `Library/` - Theorem files with `@[target]` annotations and `sorry` proofs
- `Library.lean` - Root import file
- `lakefile.lean` - Lake build configuration
- `lake-manifest.json` - Dependency manifest

## Source
Theorems with ≤22 dependencies, randomly sampled

## Usage with Agora
```bash
lake update
lake build
```
Then point Agora to this repository URL.

## Dependencies
- Lean 4 (v4.17.0)
- Mathlib4 (v4.17.0)
- VerifiedAgora
