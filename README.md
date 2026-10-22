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


## v1.4 losses and effective population size

A new livestock-loss ledger records exposure, deaths and survivors after every disease/heat challenge. Cumulative deaths are shown for each herd, and a separate CSV exports challenge events. Calendar years and monetary losses are not inferred. Herd replacement through breeding does not erase previous losses. Each breeder's panel now shows the numbers of male/female parents selected and approximate Ne = 4NmNf / (Nm + Nf). This is an elementary sex-ratio approximation, not a pedigree-based or genomic estimate.


## New in v1.4

- Added an automatic history graph for current herd size and cumulative deaths for Breeder A and Breeder B.
- The graph updates after each breeding generation, after breeding to the selected target generation, and after each challenge event.
- This graph is intended to help students follow accumulating losses over time without converting outcomes into money.
