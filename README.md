# Cattle Breeding & Genetic Resilience Lab

Independent educational population-genetics simulator for GitHub Pages, inspired by the *teaching approach* of animated population genetics simulations. All code is contained in `index.html`; no server, third-party library, tracking, or external data dependency.

## Publish

Create a public GitHub repository, add `index.html` to its root, then enable **Settings → Pages → Deploy from a branch → main → /(root)**. Or open `index.html` locally.

## Classroom experiment

Two herds begin with exactly the same randomly generated individual cattle. Breeder A emphasises milk potential, size, and docility using few parents; breeder B balances those traits against disease resistance and heat tolerance and has more breeding parents. Advance generations, expose to disease/heat challenge, press *Record current results*, and export raw CSV. The app **does not calculate differences or allele loss for students**.

Change parent numbers and recombination to isolate drift, selection and linkage; use the seed to replicate runs. The scenario deliberately introduces initial negative linkage disequilibrium between milk and resistance alleles. Production selection does *not* invariably remove resilience. The five loci, parameter weights, and stress survival function are invented pedagogical assumptions, not empirical cattle estimates. Real traits are polygenic, environmental and often complex.

## Sources and limitations

Scientific motivation: FAO Second Global Assessment of Animal Genetic Resources; FAO 2010 *Breeding Strategies for Sustainable Management of Animal Genetic Resources*; FAO *Animal Genetic Resources and Adaptation*. This app is neither endorsed by FAO nor an FAO model.

Educational software, freely usable and modifiable under MIT licence (see LICENSE).
