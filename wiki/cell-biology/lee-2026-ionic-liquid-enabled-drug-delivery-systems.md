---
title: "Ionic Liquid-Enabled Drug Delivery Systems: Benefits, Limitations, and Future Perspectives"
authors: Daeyeong Lee, Sooa Lim
year: 2026
doi: 10.3390/pharmaceutics18020224
source: lee-2026-ionic-liquid-enabled-drug-delivery-systems.md
category: cell-biology
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/lee-2026-ionic-liquid-enabled-drug-delivery-systems.pdf
pdf_filename: lee-2026-ionic-liquid-enabled-drug-delivery-systems.pdf
source_collection: external
tags: [ionic-liquid, drug-delivery, DDS, review, nanocarrier, microneedle, PIL, transdermal, oral-delivery, injectable, API-IL, biocompatibility, antimicrobial, structure-activity]
---

## Summary
Framework-driven 2026 review (Pharmaceutics, MDPI) positioning ionic liquids (ILs) as **formulation-enabling materials rather than standalone therapeutics**. It surveys IL-enabled drug delivery systems (DDS) **by platform** — nanocarriers, microtechnology, biomacromolecules — treating administration route (transdermal/oral/injectable) as a contextual variable rather than the organizing axis. The central thesis: IL value is in *structure-dependent, application-specific adaptability*, and the same **membrane-active behavior** that enhances solubility/permeability also drives antimicrobial activity and toxicity — so rational ion design and safety evaluation are inseparable. ILs are strictly defined as room-temperature ionic salts; **deep eutectic solvents (DESs) are explicitly excluded** (the complementary [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] perspective covers both — see note below).

## Key Contributions
- **Platform-based organization** (nanocarrier / microtechnology / biomacromolecule) instead of route-based, surfacing shared design principles across routes
- **Three-generation analytical framework** for ILs: 1st gen solvent-oriented (imidazolium/pyridinium) → 2nd gen task-specific (TSILs) → 3rd gen biocompatibility/application-oriented (choline + amino-acid / API-IL)
- Unifies **structure–property–function** (delivery) and **structure–activity–toxicity (STARs)** (antimicrobial/safety) through one driver: **IL–membrane interaction**
- Reframes IL antimicrobial activity as a *secondary, structure-dependent manifestation of membrane interaction* — not a primary DDS objective
- Critical consolidation of translational barriers: structure-dependent toxicity, no standardized evaluation criteria, scalability, regulatory ambiguity
- Explicit scope boundary: ILs only, DESs excluded as conceptually distinct

## Methodology and Architecture
Narrative critical review, three pillars:

**1. IL generations (analytical, not chronological)**

| Generation | Representative cations | Anions | Focus | Key limitation |
|---|---|---|---|---|
| 1st (solvent) | imidazolium [C4mim]+, pyridinium | [AlCl4]−, PF6−, BF4− | green solvent substitute; thermal stability, negligible vapor pressure | hydrolytic instability, poor biodegradability, toxicity |
| 2nd (task-specific, TSIL) | imidazolium, quaternary ammonium | PF6−, BF4−, TFSI− | moisture/air stability, functional control (biocatalysis) | cost, low aqueous compatibility, structure-dependent toxicity |
| 3rd (biocompatible/applied) | choline+, amino-acid cations | organic/amino acids, API-derived (API-IL) | biocompatibility, pharmacological relevance, DDS formulation flexibility | limited long-term safety/regulatory data |

**2. Platform survey**
- **Nanocarriers** — ILs/PILs as solubilizers, stabilizers, surface modifiers; EPR tumor targeting; pH/light-responsive release
- **Microtechnology** — PIL microneedles (mechanical strength + intrinsic antimicrobial); IL microemulsions (surfactant substitution, dermal permeation)
- **Biomacromolecules** — proteins, nucleic acids, peptides, vaccines: native-structure preservation, enzymatic-degradation resistance, intracellular delivery, ambient/refrigerated storage stability

**3. Antimicrobial properties + cross-cutting limitations**

## Results
**Representative formulations (from review tables):**
- **ImIL-PEG@MCM-41 / lapatinib** — ~150 nm, EE ~91%, pH-responsive release for tumor microenvironment
- **Imidazolium-IL/alginate/clay + MTX + ciprofloxacin** — ~70 nm, EE ~99%/98%, pH-responsive co-delivery
- **PIL block copolymer (P[VHim]NTf2) + doxorubicin** — 40–80 nm, loading ~70%, dual pH/UV-triggered release
- **PIL microneedles + salicylate** — antibacterial/anti-inflammatory vs. *C. acnes*; **NO-releasing PIL microneedles** — antibiofilm + wound healing
- **Choline IL transdermal insulin** — enhanced transport with skin compatibility
- **Favipiravir API-IL** — 78–125× aqueous solubility, improved oral bioavailability
- **[Ch][Tre]–[Ch][Ger] / tretinoin** — extreme apparent solubilization (~10^8-fold vs. water), 95–97% release at 5 min
- **Choline oleate co-aggregates / paclitaxel** — injectable solubilization

**Antimicrobial structure–activity:**
- Activity ∝ cation alkyl-chain length (>~4 carbons lowers MIC via stronger membrane interaction); imidazolium/pyridinium > quaternary ammonium; long-chain cholinium/imidazolium most antibiofilm
- Generally more active vs. **Gram-positive** (Gram-negative outer membrane confers tolerance)
- ampicillin-IL beats halide salt vs. resistant *E. coli*/MRSA; long-chain ILs act as **colistin adjuvants**
- Membrane mechanism → slower resistance but non-selective → cytotoxicity; **activity–toxicity trade-off**

## Benefits vs. Limitations (the paper's framing)
**Benefits:** tunable physicochemistry; API–IL complexation; solubility/permeability/stability gains; controlled membrane interaction; formulation flexibility; reduced organic-solvent use.
**Limitations:** structure-dependent cytotoxicity (same trends as efficacy); poor/unclear biodegradability and ecotoxicity (low volatility ≠ low ecological risk); no standardized evaluation criteria; scalability (microneedle robustness, microemulsion ratio sensitivity, viscosity); regulatory ambiguity (ILs not established excipients). The authors caution ILs are **not universally superior** to mature polymeric/lipid carriers.

## Related Papers
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — complementary 2026 IL review focused on nucleic-acid biopharmaceuticals that **includes DESs**; this paper deliberately excludes DESs (the two together bracket the IL-DDS review landscape)
- [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]] — founding CAGE/cholinium IL work for transdermal delivery and pathogen neutralization (a primary source behind this review's transdermal/antimicrobial sections)
- [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]] — 10-year CAGE review; concrete clinical-stage instance of the transdermal/oral IL-DDS this review generalizes
- [[cell-biology/greene-2019-scope-and-efficacy-of]] — CAGE antibiofilm efficacy across ESKAPE pathogens (membrane-active antimicrobial mechanism)
- [[cell-biology/ko-2020-clinical-translation-of-choline]] — clinical translation of a choline IL (the regulatory/translation gap this review highlights)
- [[computational/yu-2026-ionic-liquids-as-alternative]] — choline IL as an LNP component for mRNA (biomacromolecule IL-DDS in practice)
- [[overviews/ionic-liquid-rna-storage-state-and-hydrolysis]] — overview of IL-based nucleic-acid stabilization (the storage/stability angle of biomacromolecule IL-DDS)
