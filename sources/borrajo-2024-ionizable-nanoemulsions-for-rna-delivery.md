---
title: "Ionizable nanoemulsions for RNA delivery into the central nervous system – importance of diffusivity"
authors: Mireya L. Borrajo, Aloia Quijano, Philipp Lapuhs, Ana I. Rodriguez-Perez, Shubaash Anthiya, José L. Labandeira-Garcia, Rita Valenzuela, María José Alonso
year: 2024
doi: 10.1016/j.jconrel.2024.06.051
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/borrajo-2024-ionizable-nanoemulsions-for-rna-delivery.pdf
pdf_filename: borrajo-2024-ionizable-nanoemulsions-for-rna-delivery.pdf
source_collection: external
---

## One-line Summary
Ionizable nanoemulsions (iNEs) — a soft, fluid Vitamin E oily core combined with the ionizable lipid C12–200, DOPE, and DMG-PEG — package siRNA/mRNA into sub-100 nm, neutral-surface particles that diffuse far better than rigid-core LNPs across rat brain (~3.4 mm vs 1–2.7 mm for LNPs) and selectively transfect neurons after intra-parenchymal injection.

## 1. Document Information
- **Journal**: Journal of Controlled Release **372** (2024) 295–303 (Elsevier)
- **DOI**: 10.1016/j.jconrel.2024.06.051; received 14 May 2024, accepted 20 June 2024, online 24 June 2024
- **License**: Open access, CC BY-NC
- **Type**: Original research article
- **Affiliations**: CiMUS, Dept. of Pharmacy & Pharmaceutical Technology, and IDIS, University of Santiago de Compostela (Spain); CIBERNED (Madrid). Alonso group.
- **Funding**: EU Horizon 2020 B-SMART (No 721058); Xunta de Galicia; Spanish Ministry of Science (PID2021-126848NB-100); ISCIII i-PFIS (IFI19/00033). C12–200 and DMG-PEG2000 gifted by Muthiah Manoharan, Alnylam Pharmaceuticals.

## 2. Key Contributions
- Introduces **ionizable nanoemulsions (iNEs)** as a new class of RNA carrier: replaces the dense, rigid core of classical LNPs with a **soft, fluid, deformable oily (Vitamin E) core** to overcome the limited tissue diffusivity that hampers LNPs in the CNS.
- Demonstrates **enhanced brain diffusivity**: GFP-expressing cells detected up to **~3.4 mm** from the injection site, vs the **1–2.7 mm** typical of mRNA-LNPs in the literature — supporting the hypothesis that core deformability (not just size/PEG) drives diffusion.
- Shows a **single robust formulation** carries both siRNA and mRNA (siGFP silencing; mGFP expression) with sub-100 nm size, neutral charge, and 80–90% encapsulation.
- Reports **neuron-selective transfection** in vivo after intra-parenchymal (intrathalamic) administration, with apparent evasion of microglia — relevant for glioblastoma and Parkinson's disease.

## 3. Methodology and Architecture

### Formulation
- **Components & molar ratio**: C12–200 (ionizable lipid) : DOPE (helper lipid) : Vitamin E (D,L-α-tocopherol, oily core) : DMG-PEG2000 = **35 : 16 : 46.5 : 2.5**.
- **N/P ratio** (C12–200 amines : RNA phosphates) = **15:1**; full RNA entrapment achieved at this ratio.
- **Microfluidic mixing** (NanoAssemblr, Precision NanoSystems), solvent-displacement: organic phase (lipids in EtOH) + aqueous phase (RNA in 10 mM citrate buffer, pH 4); flow-rate ratio 1:5 (organic:aqueous), total flow 12 mL/min. A bulk-mixing Tween 80® variant was also screened.
- **C12–200 behavior**: cone-shaped multi-tail ionizable lipid; **positively charged at acidic pH** (condenses RNA, boosts endosomal disruption), **neutral at physiological pH**.

### Characterization
- DLS (size, PDI) and laser-Doppler ζ-potential (Zetasizer Nano ZS).
- **Encapsulation efficiency**: agarose gel electrophoresis (qualitative; Triton X-100 disruption and heparin displacement) + Quant-iT RiboGreen assay (quantitative).
- Release probed by dilution in citrate buffer (pH 4) vs PBS (pH 7.4).

### Biological evaluation
- **In vitro**: HeLa-GFP (siGFP silencing, resazurin viability, flow cytometry, 250→10 nM); neuron (SH-SY5Y), astrocyte (C6 glioma), microglia (CHME-3) models with mGFP (MTT viability, flow cytometry, 5 µg/well).
- **In vivo**: male Sprague-Dawley rats (n=3 iNE-mGFP + 1 PBS), stereotaxic intra-parenchymal (intrathalamic) injection of 3 µg mGFP in 3 µL, 0.5 µL/min; sacrifice at 24 h; immunofluorescence for βIII-tubulin (neurons), GFAP (astrocytes), Iba-1 (microglia), Hoechst nuclei; confocal microscopy. Double anti-GFP/βIII-tubulin labelling used to overcome neuronal autofluorescence.

## 4. Key Results and Benchmarks
- **Physicochemical** (Table 1): siGFP iNE 64 ± 7 nm, PDI 0.23, ζ ≈ −2 mV, EE 80–90%; mGFP iNE 72 ± 9 nm, PDI 0.17, ζ ≈ −4 mV, EE 80–90%. Microfluidics reduced size vs bulk mixing (initial bulk Tween80 formulation ~165 nm, +20 mV).
- **Release/complexation**: no free RNA at pH 4; at pH 7.4 most RNA stays complexed (needs Triton X-100 for full release).
- **PEG screen**: DMG-PEG2000 gave higher cell viability than Tween 80® at high doses, comparable transfection → DMG-PEG2000 (microfluidic) selected. siRNA silencing seen even at very low concentration.
- **In vitro transfection**: >70% GFP-positive cells across neurons, astrocytes, microglia, with no toxicity; MFI significantly raised in neurons and microglia (astrocytes lower, possibly lower uptake/trafficking).
- **In vivo**: distinct GFP signal in **neurons**, with **specificity for neurons over astrocytes and microglia** (contrasting the in vitro microglia uptake — a known in vitro/in vivo discrepancy); diffusion of GFP-expressing cells up to **~3.4 mm** from the injection site.

## 5. Limitations and Future Work
- **Direct CNS (intra-parenchymal) administration only** — does not address blood-brain-barrier crossing or systemic delivery.
- **Very small in vivo cohort** (3 iNE + 1 control rat); single 24 h timepoint; **GFP reporter only**, no therapeutic/disease efficacy.
- **In vitro–in vivo discrepancy** in microglia transfection unexplained (authors invoke protein-corona-driven uptake differences).
- Diffusion estimated from fluorescence close-ups (Suppl. figs), not a dedicated quantitative diffusivity assay; site/rate of injection may confound.
- Biodistribution may differ under disease conditions (glioblastoma, Parkinson's); long-term safety and C12–200 backbone biodegradability not assessed here.

## 6. Related Work
- **Classical LNPs** (Onpattro®, Comirnaty®, Spikevax®): ionizable lipid + cholesterol + helper lipid + PEG-lipid; the dense rigid core whose limited brain diffusivity motivates this work.
- **C12–200 / ionizable lipid toolbox**: Jayaraman 2012; Han et al. 2021 "An ionizable lipid toolbox for RNA delivery" (Nat. Commun.); next-gen biodegradable ionizable lipids (Jörgensen 2023, Chen 2023, Xue 2024).
- **Cationic NEs for nucleic acids**: DOTAP-containing nanoemulsions for intranasal siRNA (anti-TNF-α; anti-CD73 glioblastoma) — prior NE-RNA efforts that did not dissect deformability.
- **Brain LNP diffusion**: Rungta 2013 (PTEN-siRNA, ~1 mm); striatal Cy5-mRNA LNPs (1–1.5 mm); Cre-mRNA LNPs (1.2–2.7 mm) — the diffusivity benchmarks iNEs exceed.
- Within this wiki: contrasts with the IL-based RNA-delivery cluster (Tanaka LBILs, Yu IL-LNPs) and the LNP-engineering/storage reviews.

## 7. Glossary
- **iNE (Ionizable Nanoemulsion)**: oil-in-water nanoemulsion with a soft Vitamin E core plus an ionizable lipid (C12–200), DOPE, and PEG-lipid; designed for high tissue diffusivity in RNA delivery.
- **C12–200**: cone-shaped multi-tail ionizable lipid; protonates at acidic endosomal pH to condense RNA and disrupt endosomes, neutral at physiological pH.
- **DOPE**: 1,2-dioleoyl-sn-glycero-3-phosphoethanolamine; fusogenic helper lipid aiding endosomal escape.
- **Vitamin E (D,L-α-tocopherol)**: the fluid oily core providing deformability.
- **DMG-PEG2000**: PEGylated lipid for colloidal stabilization and reduced size; replaced the Tween 80® surfactant used in initial screening.
- **Diffusivity**: ability of the nanocarrier to spread through tissue from the administration site — the central design goal for CNS delivery here.
- **N/P ratio**: molar ratio of carrier amine groups to RNA phosphate groups (15:1).
- **Intra-parenchymal administration**: direct injection into brain tissue (here intrathalamic), bypassing the BBB.
</content>
