---
title: "Ionic liquids: prospects for nucleic acid handling and delivery"
authors: Ksenia S. Egorova, Alexandra V. Posvyatenko, Sergey S. Larin, Valentine P. Ananikov
year: 2021
doi: 10.1093/nar/gkaa1280
source: egorova-2021-ionic-liquids-prospects-for-nucleic.md
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/egorova-2021-ionic-liquids-prospects-for-nucleic.pdf
pdf_filename: egorova-2021-ionic-liquids-prospects-for-nucleic.pdf
source_collection: external
tags: [ionic-liquid, nucleic-acid, gene-delivery, siRNA, pDNA, transfection, CAGE, IL-robed-oligonucleotide, lipofection, zeta-potential, structure-activity, review]
---

## Summary
The foundational, mechanism-first review (Nucleic Acids Research 2021) of ionic liquids for **nucleic-acid handling and delivery**. It treats ILs as **tunable hierarchical media** whose nano/micro-structuring underlies their ability to stabilize nucleic acids (duplex/triplex/G-quadruplex), protect them from nucleases, and aid translocation across the cell membrane. The practical core for a delivery developer is **Table 6**, which catalogs essentially every IL gene-delivery study to 2021 with formulation, cell line, readout, and outcome. If you are starting RNA-delivery work, this is the "map of the field" to read first.

## Key Contributions
- Connects IL physical chemistry (structuring, tunability, ~10^18 ion combinations) to nucleic-acid behaviour and delivery performance
- Comprehensive catalog of IL/IL-like delivery agents: **simple ILs, cationic amphiphiles, Gemini surfactants, poly(ILs), and "IL-robed" self-delivering oligonucleotides**
- Defines ideal gene-delivery-agent criteria and positions ILs primarily within **polymer- and lipid-mediated** delivery
- Separates the more mature **handling/storage/extraction** uses (sequencing, PCR templates, biosensors) from the emerging **therapeutic delivery** uses

## Methodology and Architecture
Narrative review in three parts:
1. **ILs as tunable hierarchical systems** + nucleic-acid behaviour in IL/IL–water media
2. **Survey of delivery techniques** (physical / non-viral / viral) for context
3. **IL application in delivery**, organized by compound class → culminating in Table 6

## Results
Selected systems from Table 6 (most relevant to RNA/oligo delivery):

| IL system | Cargo | Outcome |
|---|---|---|
| [C4Mim][PF6] + Lipofectamine | pDNA (eGFP) | nanostructure formation via phosphate electrostatics; protects vs. 120 min sonication; **enhanced transfection** (COS-7/HEK293/HeLa), low toxicity |
| **CAGE + CAPA (25% v/v each)** | **siRNA (GAPDH, NFKBIZ)** | stabilizes siRNA; **efficient in vivo epidermal siRNA delivery** (~0.20 nmol·cm⁻²); no skin irritation; psoriasis-oriented |
| bis(alkoxy)benzyl imidazolium halide (C12) + DOPE | **siRNA (luciferase)** | knockdown comparable to Lipofectamine 2000 at 10 nM; ~70 nm, **+zeta** → endocytosis; complexation depends on alkyl chain length, not anion |
| dicationic imidazolium IL in DPPC:DOPE liposome (20 mol%) | pDNA (GFP) | efficient HeLa transfection |
| double-chained pyridinium amphiphiles | DNA | clear SAR: chain length ↓toxicity & ↓transfection; C18:1 unsaturation ↑transfection; trans > cis |

**Design takeaways for RNA delivery:**
- **Cationic head + lipophilic tail** is the recurring motif — electrostatics condense the polyanionic RNA, lipophilicity drives membrane crossing.
- **Alkyl chain length** is the master tuning knob for both complexation strength and the efficacy/toxicity balance; **anion choice** affects complexation less than the cation.
- **Helper lipids (DOPE)** and **~70 nm, positively charged complexes** recur in the best-performing siRNA systems (cell-surface binding + endocytosis).
- The **CAGE/CAPA** route shows ILs can self-deliver siRNA across skin in vivo without a separate nanocarrier.

## Limitations
- Most therapeutic-delivery evidence is in vitro / proof-of-concept; field young as of 2021
- Cytotoxicity tracks the same lipophilicity that drives delivery (activity–toxicity trade-off)
- Nanoparticle / CPP / VLP routes flagged as promising but under-explored

## Related Papers
- [[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]] — later (2024) review focused specifically on IL **nano** delivery of nucleic acids; read after this for the updated/translational picture
- [[computational/sagitha-2023-choline-ester-based-ionic-liquid]] — concrete experimental instance of the cationic-choline-IL + DNA complexation + cell-penetration motif catalogued here
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — narrower successor on IL/DES for siRNA/mRNA/ASO biopharmaceuticals
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — the storage/stabilization side (small-RNA, +Tm) of IL–nucleic-acid science
- [[cell-biology/lee-2026-ionic-liquid-enabled-drug-delivery-systems]] — broad IL-DDS review that cites this paper in its nucleic-acid section
- [[overviews/ionic-liquid-rna-storage-state-and-hydrolysis]] — overview synthesizing IL-based RNA storage/stability
