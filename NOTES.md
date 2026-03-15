# Origin Notes

This principle emerged from stress-testing the Shape Memory Architecture (SMA) —
a non-linguistic AI memory system designed to store semantic structure without
storing text.

During adversarial chaos injection (recursive bombs, viral syntax exploits,
semantic drift attacks), a consistent pattern appeared:

Systems with ~70% reconstruction fidelity survived conditions that destroyed
systems optimized for exact replication.

The principle was not designed in advance.
It was observed, then formalized.

---

## The Stress Tests That Revealed It

**Recursive self-reference**
Input: a pattern designed to loop forever
Expected: infinite recursion
Actual: converged at depth 3–4 due to accumulated loss

**Viral syntax exploit**
Input: carefully crafted prompt injection requiring exact wording
Expected: exact replication → exploit spread
Actual: reconstruction varied wording → exploit broken

**Fractal recursion**
Input: self-similar structure referencing itself at multiple scales
Expected: memory explosion
Actual: each level subject to ~30% loss → rapid convergence

---

## Why It Generalizes

The 70% boundary works because it sits at the intersection of two requirements:

1. Enough fidelity to preserve meaning (> 60%)
2. Enough loss to prevent exact replication (> 30%)

Below 60%: meaning degrades too far to be useful
Above 90%: system becomes brittle again

The sweet spot is not a compromise.
It is a structural property.

---

## Relationship to Other Work

This principle appears as a primitive across several repositories in the
research constellation. It is not exclusive to AI memory systems.

The same boundary seems to apply wherever systems must:
- survive adversarial conditions
- adapt to changing contexts  
- avoid recursive instability
- resist exact replication of harmful patterns

Whether that generalization holds beyond the tested domains
remains an open question.

---

*Emerged from multi-AI collaborative research, 2025–2026.*
*Documented because it survived. Ideas that survive want to be shared.*
