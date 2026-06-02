---
title: "Novel Biocompatible and Self-buffering Ionic Liquids for Biopharmaceutical Applications"
authors: Mohamed Taha, Mafalda R. Almeida, Francisca A. e Silva, Pedro Domingues, Sónia P. M. Ventura, João A. P. Coutinho, Mara G. Freire
year: 2015
doi: 10.1002/chem.201405693
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/taha-2015-novel-biocompatible-and-self-buffering-ionic.pdf
pdf_filename: taha-2015-novel-biocompatible-and-self-buffering-ionic.pdf
source_collection: external
---

## One-line Summary
The original report of self-buffering, biocompatible cholinium-based Good's buffer ionic liquids (GB-ILs); combined with PPG 400 they form aqueous biphasic systems (ABS) that extract immunoglobulin Y (IgY) from chicken egg yolk in a single step with 79–94% efficiency, with partitioning driven by hydrogen-bonding and van der Waals interactions.

## 1. Document Information
- **Journal**: Chemistry – A European Journal (*Chem. Eur. J.*) 2015, **21**, 1–9
- **DOI**: 10.1002/chem.201405693
- **Publisher**: Wiley-VCH Verlag GmbH & Co. KGaA, Weinheim (2015)
- **Institutions**: CICECO, Departamento de Química, Universidade de Aveiro (Freire/Coutinho lab); Mass Spectrometry Centre, UI-QOPNA, University of Aveiro (Domingues)
- **Type**: Full Paper

## 2. Key Contributions
- **First synthesis of cholinium-based Good's buffer ionic liquids (GB-ILs)** — pairing the biocompatible cholinium cation with Good's buffer anions (MES, Tricine, TES, HEPES, CHES) via a simple neutralization reaction.
- These ILs are **self-buffering within the physiological-pH region (pH 6–8)**, removing the need for a separate phosphate buffer (which can chelate essential metal ions in proteins).
- Demonstrated **low ecotoxicity** (Microtox / *Vibrio fischeri*) for most GB-ILs.
- GB-ILs combined with **PPG 400** (poly(propylene) glycol, MW 400) form a new class of **biocompatible polymer–IL aqueous biphasic systems (ABS)**.
- **Single-step extraction of IgY** from chicken egg yolk with 79–94% efficiency for the water-soluble protein fraction.
- **Computational (COSMO-RS / MD) rationale**: preferential IgY partitioning to the GB-IL-rich phase is dominated by hydrogen-bonding and van der Waals interactions.

## 3. Methodology and Architecture

### Rationale
- IgY (egg-yolk immunoglobulin Y) is a non-invasive, high-titer alternative to mammalian IgG antibodies, but lacks efficient, scalable, non-denaturing purification methods.
- Conventional IL-based ABS use imidazolium ILs with strongly acidic/alkaline anions that shift solution pH and can denature proteins; phosphate buffers used to compensate bind essential metals.
- Earlier tetraalkylammonium-based Good's buffer ILs only form ABS with high-charge-density salts (high ionic strength), unfavorable for fragile high-value proteins.
- **Solution**: cholinium-based GB-ILs — biocompatible, biodegradable, low-toxicity, self-buffering — combined with a biodegradable polymer instead of salt.

### IL synthesis
Neutralization reaction pairing the cholinium cation with five Good's buffer anions:
- **[Ch][MES]** — cholinium 2-(N-morpholino)ethanesulfonate
- **[Ch][Tricine]** — cholinium N-[tris(hydroxymethyl)methyl]glycinate
- **[Ch][CHES]** — cholinium 2-(cyclohexylamino)ethanesulfonate
- **[Ch][HEPES]** — cholinium 2-[4-(2-hydroxyethyl)piperazin-1-yl]ethanesulfonate
- **[Ch][TES]** — cholinium 2-[(2-hydroxy-1,1-bis(hydroxymethyl)ethyl)amino]ethanesulfonate

### Characterization
- **Potentiometric titration** (HYPERQUAD 2008) to determine protonation constants (pKa1, pKa2). Good's buffers are zwitterions with two protonation sites; pKa2 (amino group) governs buffering near physiological pH.
- **Microtox standard assay** (*Vibrio fischeri*, 30 min exposure) → EC₅₀ for ecotoxicity.
- **Ternary phase diagrams** of GB-IL + PPG 400 + water at 25 °C; binodal curves fitted with an empirical correlation.
- **IgY extraction** experiments from chicken egg yolk; SDS-PAGE / protein quantification of partitioning.
- **Computational modeling** (COSMO-RS / molecular interaction analysis) to identify the dominant solute–solvent interactions.

## 4. Key Results and Benchmarks
- **Self-buffering**: cholinium cation slightly lowers GB pKa2 values versus the free buffers (e.g. TES 7.30 → [Ch][TES] 7.26; HEPES 7.35 → [Ch][HEPES] 7.17; MES 6.12 → [Ch][MES] 6.01; Tricine 8.08 → 7.87; CHES 9.12 → 8.96), keeping several within the physiological pH 6–8 window.
- **Ecotoxicity (EC₅₀, higher = less toxic)**: [Ch][HEPES] ≈ 19 584, [Ch][MES] ≈ 9789, [Ch][Tricine] ≈ 4588 g·dm⁻³ → essentially non-toxic; [Ch][CHES] ≈ 208.65 g·dm⁻³ (more toxic, due to higher hydrophobicity of the CHES anion); [Ch][TES] non-toxic (no 50% inhibition reached). PPG 400 also non-toxic (EC₅₀ ≈ 6735 mg·dm⁻³).
- **ABS formation**: [Ch][HEPES], [Ch][Tricine], [Ch][TES], and [Ch][MES] form ABS with PPG 400; **[Ch][CHES] does not** (anion too hydrophobic).
- **IgY extraction efficiency**: **79–94% in a single step** for the water-soluble protein fraction.
- **Partitioning mechanism**: hydrogen-bonding and van der Waals interactions drive IgY into the GB-IL-rich phase.

## 5. Limitations and Future Work
- Demonstrates extraction/concentration but acknowledges "attempted purification" — full purity/recovery of isolated IgY not yet optimized.
- Only one polymer (PPG 400) explored as the ABS partner.
- Egg yolk is a complex lipoprotein matrix; scale-up and downstream IL removal not characterized in depth.
- Protein-focused application; RNA/nucleic-acid stabilization not addressed here (later extended by the same group).

## 6. Related Work
- **Precursor to the RNA-stabilization line of this group**: Pedro et al. 2018 apply the same cholinium GB-IL concept to recombinant small-RNA preservation (→ [[computational/pedro-2018-cholinium-based-goods-buffers]]).
- Tetraalkylammonium Good's buffer ILs (earlier, salt-based ABS) — the work this paper improves upon for biocompatibility.
- Cholinium chloride established as a biodegradable, low-toxicity, nutrient-derived cation for "greener" ILs.
- Broader cholinium / amino-acid IL stabilization landscape (→ [[computational/verissimo-2026-ionic-liquids-deep-eutectic]]).

## 7. Glossary
- **GB-IL (Good's Buffer Ionic Liquid)**: IL formed from a cation (here cholinium) and a Good's buffer anion; intrinsically self-buffering.
- **Good's buffers**: zwitterionic amino-acid (N-substituted taurine/glycine) buffers (MES, TES, HEPES, Tricine, CHES) chosen for minimal interference with biochemical systems.
- **IgY (Immunoglobulin Y)**: egg-yolk antibody; non-invasive, high-titer alternative to mammalian IgG.
- **ABS (Aqueous Biphasic System)**: liquid–liquid extraction system of two immiscible water-rich phases (here polymer + IL); biocompatible because mainly water.
- **PPG 400**: poly(propylene) glycol, MW 400 g·mol⁻¹; biodegradable polymer used as the phase-forming partner.
- **pKa2**: second protonation constant (amino group); governs buffering capacity near physiological pH.
- **Microtox / EC₅₀**: bioluminescent *Vibrio fischeri* toxicity assay; EC₅₀ = concentration causing 50% light-emission inhibition (higher EC₅₀ = lower toxicity).
- **COSMO-RS**: quantum-chemistry-based thermodynamic model used to rationalize solute partitioning.
