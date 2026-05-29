---
title: "An Efficient Method for Long-Term Room Temperature Storage of RNA"
authors: Anne-Lise Fabre, Marthe Colotte, Aurelie Luis, Sophie Tuffet, Jacques Bonnet
year: 2014
doi: 10.1038/ejhg.2013.145
source: fabre-2014-efficient-method-room-temperature.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/An efficient method for long-term room temperature storage of RNA.pdf
pdf_filename: An efficient method for long-term room temperature storage of RNA.pdf
source_collection: external
tags: [RNA storage, room temperature, anhydrous, encapsulation, Arrhenius, long-term stability, RT-qPCR, Imagene]
---

## Summary
This foundational 2014 paper from the Imagene group (Fabre, Colotte, Bonnet, et al.) establishes a quantitative Arrhenius model for room-temperature RNA degradation and validates long-term RNA storage in vacuum-dried stainless steel minicapsules under anhydrous argon atmosphere. Key finding: atmospheric humidity is the dominant degradation factor; when fully excluded, RNA degrades at an extraordinarily slow rate (~0.7–1.3 cuts/1000 nt/century). The technology is compatible with RT-qPCR downstream analysis and demonstrates sequence-independent degradation kinetics in the solid state.

## Key Contributions
- Atmospheric humidity identified as major deleterious factor; partial rehydration even in solid state restores initial instability
- Quantitative Arrhenius model: Ea = 28.5 kcal/mol; RT degradation rate = 3.2×10^-13/nt/s (95% CI: 2.3–4.2/nt/s)
- Lifetime prediction: 0.7–1.3 cuts per 1000 nt per century at room temperature in anhydrous capsules
- Degradation rate proportional to RNA molecule length; sequence-independent in solid state
- RT-qPCR Cq values unchanged over simulated decades — functional RNA preserved
- Minicapsule technology: 0.2 mL glass insert in stainless steel capsule, vacuum-dried, laser-welded under argon; superior to hydrophilic commercial matrices that cannot exclude atmospheric water

## Methodology and Architecture
- RNA sources: 3,313 nt yeast β-galactosidase mRNA; human HeLa cell total RNA; E. coli bacterial total RNA
- Encapsulation: 2 µg RNA + proprietary stabilizer → glass insert → vacuum-dried → laser-welded under anhydrous argon
- Accelerated aging: 50–130°C heating in oven; humidity experiments: opened capsules at ~50% RH
- Analysis: Agilent Bioanalyzer capillary electrophoresis; quantitative agarose gel electrophoresis with ethidium bromide (Bio1D software); RT-qPCR
- Intact phosphodiester bond fraction calculated: fluorescence intensity at time t / t0, normalized by RNA size

## Results
| Parameter | Value |
|---|---|
| Activation energy (Ea) | 28.5 kcal/mol |
| RT degradation rate | 3.2×10^-13 /nt/s |
| Expected cuts/1000 nt/century | 0.7–1.3 |

- Humidity: opening capsules in 50% RH atmosphere immediately restores degradation to levels seen in solution — demonstrates that anhydrous environment is essential, not just dehydration
- Sequence independence: same degradation rate per nucleotide for mRNA, 28S rRNA (5070 nt), 23S rRNA (2904 nt) — RNA structure does not substantially alter solid-state kinetics
- Functional compatibility: no significant Cq shift in RT-qPCR over simulated decades — stored RNA is analytically useful

## Related Papers
- [[computational/colotte-2023-reference-materials-sars-cov-2]] — application of this technology to SARS-CoV-2 RNA controls; uses same Arrhenius model for 10-year validation
- [[computational/lou-2014-review-room-temperature-storage]] — concurrent review citing this work and comparing storage modalities
- [[computational/berleant-2026-enabling-global-scale-nucleic]] — scales room-temperature nucleic acid storage to millions of samples using silica encapsulation
- [[transcriptomics/kornienko-2024-rna-stability-review-structural]] — broader review of RNA stability mechanisms including humidity effects
- [[computational/cardona-ospina-2019-systematic-review-fta-cards]] — comparison with FTA cards as alternative room-temperature RNA storage
