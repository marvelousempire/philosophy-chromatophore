# 002 — Must Haves and Must Denies

**Dynamic yet modular.** The word **yet** is binding: flexibility is permitted only while boundaries remain intelligible and independently testable.

| Rule | Must have | Must deny when | What to record |
|---|---|---|---|
| DYM-01 | Adapt within the agreed task and device limits | The design is needlessly frozen and cannot accept an in-scope change | Change request, demonstration before/after |
| DYM-02 | Independent components with explicit inputs, outputs and owners | A small change forces unrelated modules to be rewritten or reveals undeclared coupling | Owner and interface map, dependency check |
| DYM-03 | Reuse by composition without erasing source meaning | Work is duplicated or source context silently overwritten | Source lineage, reuse decision |
| DYM-04 | Preserve identity, state and recovery | An adaptive change loses user work, permissions or recoverability | State comparison and recovery test |
| DYM-05 | Function and form remain coordinated but separately accountable | Visual polish is claimed as proof of behavior or behavior bypasses authorization | Function and form witness receipts |
| DYM-06 | Local-first private operation with scoped permissions | Private information is transferred or authority extended without approval | Permissions and data-flow evidence |
| DYM-07 | Honest proof and real acceptance | A concept, documentation, mocked tile or untested code is described as a deployed application | Actual tests, device, result, unmet steps |

## Decision gate

**PASS** only with specific evidence for all rules applicable to the change. **MUST DENY** a demonstrated violation. **HOLD / UNKNOWN** when evidence is missing: unknown is not a false finding and not approval. A denial records rule ID, observed cause, owner and remedy; it does not silently delete work. Existing higher-authority security, legal, or platform restrictions still apply.

A stable interface or fixed safety rule is not the enemy of dynamism. **Must deny** refers to unnecessary rigidity or coupling within the intended change, not stability itself.

## Scope and maturity

These are **source rules** until an actual owner engine implements and tests the checks. This file does not claim that Automata, ACT V5, Micro-Slices or MakeWay currently enforce them automatically.
