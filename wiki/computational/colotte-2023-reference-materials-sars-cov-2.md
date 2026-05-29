---
title: "Reference Materials for SARS-CoV-2 Molecular Diagnostic: Validation of Encapsulated Synthetic RNAs for Room Temperature Storage and Shipping"
authors: Marthe Colotte, Aurelie Luis, Jacques Bonnet, Delphine Coudy, Sophie Tuffet, Isabelle Robene, Babbitha Fenelon, Emmanuel Jouen, Nicolas Leveque, Sophie Alain, Dorian Plumelle, Camille Tumiotto, Laurent Busson, Marie-Edith Lafon
year: 2023
doi: 10.1101/2023.08.28.555008
source: colotte-2023-reference-materials-sars-cov-2.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Reference_materials_for_SARS-CoV-2_molecular_diagn.pdf
pdf_filename: Reference_materials_for_SARS-CoV-2_molecular_diagn.pdf
source_collection: external
tags: [RNA storage, room temperature, encapsulation, SARS-CoV-2, RT-PCR, RT-LAMP, reference materials, diagnostics, RNAshells]
---

## Summary
This 2023 bioRxiv preprint from the Imagene group (Colotte, Bonnet, et al.) validates that synthetic SARS-CoV-2 RNA controls encapsulated in Imagene RNAshells — metallic capsules with vacuum-dried RNA under anhydrous argon/helium — remain fully functional for COVID-19 molecular detection (RT-qPCR and RT-LAMP) after accelerated aging equivalent to 10 years at room temperature. The study spans 5 independent French laboratories, 3 SARS-CoV-2 variants, 5 gene targets, 4 thermocyclers, and 6 PCR kits.

## Key Contributions
- 10-year equivalent room temperature stability confirmed by accelerated aging (90°C/16 h; Arrhenius model from Fabre et al. 2014)
- Multi-laboratory validation: 5 sites, 4 PCR platforms, 6 PCR kits, plus RT-LAMP — demonstrates robustness
- RNA retrieval satisfactory and detection reproducible across all conditions
- Room temperature shipping eliminates dry ice logistics; enables stockpiling and field deployment
- RNAshells technology: RNA vacuum-dried with proprietary stabilizer, sealed in metallic capsule under anhydrous argon/helium; inert, anoxic, anhydrous environment

## Methodology and Architecture
RNA source: Twist Bioscience synthetic SARS-CoV-2 RNA controls (3 variants: Australia/VIC01, Wuhan-Hu-1, France/HF2393); each variant = 6 non-overlapping 5 kb fragments covering >99% genome; in vitro transcribed ssRNA.

Encapsulation process:
1. Received on dry ice at ~10^6 copies/µL
2. Aliquoted at 10^4 or 10^5 copies/capsule
3. Mixed with Imagene proprietary stabilization solution
4. Vacuum-dried
5. Sealed under anhydrous argon/helium (metallic capsule)

Accelerated aging: 90°C for 16 hours = 10-year equivalent at 25°C (Arrhenius: Ea = 28.5 kcal/mol).

Recovery: ShellOpener tool → add RNAse-free water → 10-20 min rehydration → ready for RT-qPCR or RT-LAMP.

## Results
- Aged samples (10-year equivalent) produced detection results not significantly different from unaged controls
- 5 gene targets detected (E, N, RdRp, Sarbeco-E, Orf1a/b) across all variants
- RT-LAMP detection successful alongside RT-qPCR
- Technology enables large strategic batches for standardization between diagnostic sites
- Field deployment possible in locations with large temperature variation and without cold chain infrastructure

## Related Papers
- [[computational/fabre-2014-efficient-method-room-temperature]] — original Imagene capsule RNA storage method with quantitative Arrhenius lifetime prediction
- [[computational/lou-2014-review-room-temperature-storage]] — review of room temperature biospecimen storage options
- [[computational/berleant-2026-enabling-global-scale-nucleic]] — scalable room-temperature nucleic acid repositories using silica encapsulation with database-like retrieval
- [[transcriptomics/kornienko-2024-rna-stability-review-structural]] — RNA stability mechanisms including humidity as major degradation factor
