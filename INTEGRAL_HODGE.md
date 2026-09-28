# Integral Hodge is not L(D)

**Author:** Benjamin Stanley Frohman  
**Copyright:** © 2026 Benjamin Stanley Frohman  
**License:** Apache-2.0

`L(D) ⇔ Δ_miss(D) = ∅` is the rational sentence: coefficients in `Q`.

The integral Hodge conjecture replaces that with

```text
cl_Z : CH^2(X) → H^4(X, Z)
surjective onto H^4(X, Z) ∩ H^{2,2}(X).
```

It is already false in general (Atiyah–Hirzebruch; Kollár on very general hypersurfaces in `P^4`). A failure over `Z` is not a failure over `Q`.

On `V(F)`, the rational primitive class `α = [Π] − (1/6) h^2` clears to

```text
β = h^2 − 6[Π] = [S] − 5[Π] ∈ im(cl_Z).
```

`β` is not an integral miss. `α` is not a rational miss. Full ledger: `BenFrohman/HODGE-DISPROOF/docs/INTEGRAL_HODGE.md`.
