---
title: "Ionizable nanoemulsions for RNA delivery into the central nervous system – importance of diffusivity"
authors: Mireya L. Borrajo, Aloia Quijano, Philipp Lapuhs, Ana I. Rodriguez-Perez, Shubaash Anthiya, José L. Labandeira-Garcia, Rita Valenzuela, María José Alonso
year: 2024
doi: 10.1016/j.jconrel.2024.06.051
source: borrajo-2024-ionizable-nanoemulsions-for-rna-delivery.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/borrajo-2024-ionizable-nanoemulsions-for-rna-delivery.pdf
pdf_filename: borrajo-2024-ionizable-nanoemulsions-for-rna-delivery.pdf
source_collection: external
tags: [ionizable-nanoemulsion, iNE, RNA-delivery, mRNA, siRNA, CNS, brain-delivery, diffusivity, C12-200, ionizable-lipid, nanoemulsion, neuron-targeting]
---

## Summary
Borrajo et al. (2024) introduce **ionizable nanoemulsions (iNEs)** — an RNA delivery carrier that swaps the dense, rigid core of a classical lipid nanoparticle (LNP) for a **soft, fluid, deformable oily core (Vitamin E)** combined with the ionizable lipid **C12–200**, the helper lipid **DOPE**, and **DMG-PEG2000**. The motivating hypothesis: LNPs deliver RNA well but **diffuse poorly through tissue**, a critical barrier in the central nervous system (CNS). The resulting iNEs are **sub-100 nm**, **neutral on the surface**, encapsulate **both siRNA and mRNA at 80–90%**, are non-toxic, and transfect neurons, astrocytes, and microglia in vitro (>70% GFP+). In rats, after intra-parenchymal injection of mGFP-iNEs, they **selectively transfect neurons** and **diffuse ~3.4 mm** from the injection site — well beyond the 1–2.7 mm typical of mRNA-LNPs — validating the "fluid core → better diffusion" concept.

This is the wiki's example of keeping the **ionizable lipid** (the pH-switchable RNA-complexing component, as in LNPs) but changing the **particle architecture** to a nanoemulsion — distinct from the ionic-liquid routes in [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] (the lipid itself is an IL) and [[computational/yu-2026-ionic-liquids-as-alternative]] (IL replaces PEG in an LNP).

## Key Contributions
- **New carrier class (iNE)**: ionizable lipid + fluid Vitamin E core, engineered for **tissue diffusivity** rather than just transfection.
- **Enhanced brain diffusion**: GFP-expressing cells up to **~3.4 mm** from injection vs **1–2.7 mm** for literature mRNA-LNPs — attributed to the soft, deformable core (plus sub-100 nm size and surface PEG).
- **Cargo-agnostic, robust formulation**: one composition carries siRNA (silencing) and mRNA (expression) with near-identical size/charge and 80–90% encapsulation.
- **Neuron-selective in vivo transfection** after intra-parenchymal administration, with apparent microglia evasion — promising for glioblastoma and Parkinson's disease.

## Methodology and Architecture
- **Composition (molar ratio 35:16:46.5:2.5)**: **C12–200** (ionizable lipid) / **DOPE** (helper) / **Vitamin E** (oily core) / **DMG-PEG2000** (PEG-lipid). **N/P = 15:1**.
- **C12–200 chemistry**: cone-shaped multi-tail ionizable lipid — **cationic at acidic pH** (condenses RNA at formulation pH 4 and drives endosomal disruption on uptake), **neutral at physiological pH 7.4** (hence the neutral particle surface).
- **Manufacture**: microfluidic solvent-displacement (NanoAssemblr), lipids in EtOH + RNA in citrate buffer pH 4, flow-rate ratio 1:5, 12 mL/min. Microfluidics (and DMG-PEG2000) gave the sub-100 nm size vs the ~165 nm bulk-mixed Tween 80® screening formulation.
- **Characterization**: DLS/ζ-potential; encapsulation by agarose gel (Triton X-100 disruption, heparin displacement) + RiboGreen.
- **Biology**: in vitro HeLa-GFP (siGFP), and neuron (SH-SY5Y) / astrocyte (C6) / microglia (CHME-3) models (mGFP); in vivo stereotaxic intra-parenchymal (intrathalamic) injection of mGFP-iNE in rats, 24 h, immunofluorescence for βIII-tubulin / GFAP / Iba-1.

## Results
| Cargo | Size (nm) | PDI | ζ-potential (mV) | Encapsulation |
|-------|-----------|-----|------------------|---------------|
| siGFP | 64 ± 7 | 0.23 | ≈ −2 | 80–90% |
| mGFP | 72 ± 9 | 0.17 | ≈ −4 | 80–90% |

- **Release**: no free RNA at pH 4; mostly complexed at pH 7.4 (needs detergent for full release).
- **PEG choice**: DMG-PEG2000 (microfluidic) > Tween 80® on viability at high dose, equal transfection → selected.
- **In vitro**: >70% GFP+ across all three CNS cell models, no toxicity; MFI highest in neurons/microglia, lower in astrocytes.
- **In vivo**: distinct GFP in **neurons**, **selective over astrocytes/microglia**; diffusion ~**3.4 mm** from injection site. Note an in vitro→in vivo discrepancy: microglia took up iNEs in culture but appear evaded in vivo (authors invoke protein-corona effects).

## Limitations
- Direct intra-parenchymal injection only — **no BBB-crossing / systemic delivery**; small cohort (n=3+1), single timepoint, **GFP reporter only** (no therapeutic readout); diffusivity estimated from fluorescence images, not a dedicated assay.

## Related Papers
- [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] — alternative chemistry: the lipid is an ionic liquid (permanently cationic), vs the pH-switchable ionizable lipid C12–200 here.
- [[computational/yu-2026-ionic-liquids-as-alternative]] — also keeps an ionizable lipid (SM-102) in an LNP but swaps PEG for a choline IL; both papers re-engineer one LNP component (core vs stabilizer).
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — review framing of stabilization/delivery platforms for siRNA/mRNA/ASO; positions iNEs among non-LNP carriers.
- [[transcriptomics/bonetta-2009-rna-based-therapeutics-delivery]] — earlier survey identifying intracellular/tissue delivery as the central bottleneck for RNA therapeutics — the diffusivity problem iNEs target.
- [[computational/zhang-2026-chemical-engineering-mrna-lnp]] — mRNA-LNP engineering (incl. novel ionizable lipids); complementary to changing the particle architecture.
- [[computational/xian-2023-nanobiotechnology-enabled-mrna]] — nanostructure/LNP strategies for mRNA; broader nanocarrier context.
</content>
