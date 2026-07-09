# Project Piston v14 — Vehicle State Engine

Added Vehicle State Engine prototype:

- Tasks are grouped by vehicle state, not repeated isolated stages.
- Annual Service now keeps cabin filter/interior work on the ground.
- Vehicle is raised once for underside work only.
- Vehicle is lowered before oil refill/final checks.
- Timing Chain now tracks states such as RH arch access, engine supported, timing exposed.
- Auxiliary Belt tracks belt removed / belt system exposed state.
- Evidence now attaches to vehicle states.

This reduces repetition, removes ambiguity, and improves safety logic.
