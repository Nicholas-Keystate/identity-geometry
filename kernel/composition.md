# The composition law

**Tiers compose at seams: what one tier of authority declines to
answer is exactly the domain of the tier above it.**

This is the kernel's one law of its own. It was not designed; it
was noticed — the sentence "KERI detects; a GARD adjudicates"
turned out to be an instance of it, and then every other tier
boundary in the running artifacts turned out to be another.

## The anatomy of one mint

```mermaid
flowchart TB
    subgraph MINT["MEDIUM MINT: duplicity detection"]
        SIGMA["Σ — the domain<br/>pairs of events both claiming<br/>one coordinate (pre, sn)"]
        F["f — the predicate<br/>same committed bytes → sat<br/>different bytes → unsat<br/>(= duplicity detected)"]
        SEAM["SEAM — declines to evaluate<br/>WHICH voice is the true one<br/>detects, never adjudicates"]
        SIGMA --> F --> SEAM
    end
```

The seam is not a failure. It is a committed jurisdiction
statement: *this question exists, and it is not mine.*

## The five medium mints

```mermaid
flowchart LR
    subgraph MEDIUM["THE MEDIUM'S OWN MINTS (KERI — no AID is predicate-free)"]
        direction TB
        M1["duplicity detection<br/>f: byte-compare at one coordinate<br/>─────────────<br/>seam: WHICH voice is true"]
        M2["pre-rotation<br/>f: keys match prior n-commitment<br/>─────────────<br/>seam: WHY this rotation"]
        M3["superseding recovery<br/>f: attachment geometry, key<br/>generation, open window<br/>─────────────<br/>seam: thief vs rightful cure"]
        M4["first-seen<br/>f: local arrival order<br/>─────────────<br/>seam: GLOBAL order<br/>(the medium's own no-ambient)"]
        M5["delegation<br/>f: delegator anchor present<br/>─────────────<br/>seam: the delegator's reasons"]
    end
```

These five are charted, never legislated: each is a β-binding to
the protocol's committed behavior, descriptive and convictable if
misread. The kernel does not mint at the root; it charts the root.

## The tower

```mermaid
flowchart TB
    subgraph T1["TIER 1 — THE MEDIUM (charted: β-bindings to the protocol's committed spans)"]
        A1["duplicity detection<br/>seam: WHICH is true"]
        A2["pre-rotation<br/>seam: WHY rotate"]
        A3["recovery geometry<br/>seam: thief vs rightful"]
    end

    subgraph T2["TIER 2 — THE GOVERNED DOMAIN (a GARD's fold under committed law)"]
        B1["reinstatement / succession<br/>Σ = contested voices"]
        B2["rotation covenants<br/>Σ = establishment events + their law"]
        B3["recovery branch<br/>Σ = cures + declarations + horizons"]
        C1["seams of THIS tier:<br/>observer-conditional protection ·<br/>colluding continuity authority ·<br/>the both-lawful race"]
    end

    A1 -- "refused WHICH<br/>becomes Σ of" --> B1
    A2 -- "refused WHY<br/>becomes Σ of" --> B2
    A3 -- "refused thief-vs-rightful<br/>becomes Σ of" --> B3
    B1 --> C1
    B2 --> C1
    B3 --> C1
    C1 -. "the next tier's Σ<br/>(open)" .-> D["TIER 3 — ..."]
```

Reading the picture: the horizontal cut between tiers is the
detect/adjudicate boundary, an instance of the law rather than a
special arrangement. "Grounding up, governing down" is the arrows'
two directions — the lower tier's seams supply the upper tier's
domains; the upper tier's committed law pins predicates downward.
The tower does not stop: tier 2 has its own confessed seams, and
they are exactly where a third tier would begin. A deferral to
future machinery (leaving a question at a tier's seam) is a lawful
move under this law — the question sits outside the tier's Σ,
waiting for the tier that ranges over it — and is distinct from
silently evaluating it, which is the overclaim defect.

## Corollaries

- **A confessed seam is load-bearing.** Dropping a seam in
  compression is how overclaims are born; every projection of a
  mint carries its seam or is a defective binding.
- **Seam inventories predict architecture.** The set of questions
  a tier refuses is the requirements document for the tier above
  it — written by the refusals, not by a designer.
- **The tower is open at the top by construction.** The top tier's
  seams are always someone's future domain. A tower with a closed
  top has either answered every question (false for any real
  system) or silently evaluated some (the defect).
