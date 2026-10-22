# Cattle Breeding & Genetic Resilience Lab v1.2

Upload `index.html` to a GitHub Pages repository root. This standalone simulation uses no external packages.

## Teaching design
Two herds start with identical animals. Breeder A targets milk yield SI 86–100 and milk solids SI 80–100. Breeder B targets balanced SI 70–80; the default index is milk yield 25%, milk solids 20%, disease marker 15%, heat marker 15%, docility 15%, low maintenance 10%. SI values are illustrative 0–100 genetic teaching scores, not cattle EBVs.

Selection is by a percentage of candidates. Challenge events now cause stochastic actual deaths and animals are removed from the living herd. You can breed survivors further. The challenge slider scales exposure.

### Science notes
- Disease scenario is deliberately severe and illustrative, with per-animal mortality varying by simulated resistance marker; it does not predict deaths from any specific pathogen.
- Heat assumes a model 2% baseline event mortality and up to a 20% *relative increase* (2.4% total), not 20% absolute deaths.
- DGAT1 and PLAG1 are on BTA14; BoLA/MHC is on BTA23; LEP is on BTA4; GHR is on BTA20. The illustrated M-D linkage model uses a **hypothetical** nearby D marker on BTA14, not BoLA or a verified named disease locus.
- A candidate gene, QTL association, and demonstrated causal mutation are not interchangeable.

This is an educational illustration; real dairy traits and resistance are highly polygenic, and any exact mortality probabilities depend on pathogen, management, exposure and other conditions.
