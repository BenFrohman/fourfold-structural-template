<!--
INTEGRAL_HODGE.md

Copyright 2026 Benjamin Stanley Frohman

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

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
