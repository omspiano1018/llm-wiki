---
title: "Room-Temperature Preservation of mRNA using Deep Eutectic Solvent"
authors: Hoang T. Dinh, Michael Kegel, Drew Weissman, Jilian R. Melamed, Kathleen J. Stebe, Daeyeon Lee
year: 2025
doi: 10.26434/chemrxiv-2025-js4lr-v2
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/dinh-2025-room-temperature-preservation-of-mrna.pdf
pdf_filename: dinh-2025-room-temperature-preservation-of-mrna.pdf
source_collection: external
---

## One-line Summary
A simple, metal-free, hydrophobic deep eutectic solvent (hDES) of methyltrioctylammonium chloride (MTAC) and 1-decanol extracts full-length, clinically relevant mRNA at ~100% efficiency, shields it from RNase A, and preserves its integrity and translatability at room temperature for at least 227 days (~7.5 months).

## 1. Document Information
- **Type**: Preprint (ChemRxiv, posted 28 August 2025); CC BY-NC-ND 4.0; not peer-reviewed
- **Institution**: University of Pennsylvania — Dept. of Chemical & Biomolecular Engineering; Dept. of Medicine; Penn Institute for RNA Innovation (Drew Weissman group)
- **Download date**: 2026-06-24

## 2. Key Contributions
1. First report of a hydrophobic DES used to extract and preserve **full-length mRNA** (not short/model RNA) at room temperature.
2. Metal-free hDES (1-decanol : MTAC), avoiding the toxic heavy metals (e.g., NiCl₂) used in prior magnetic-DES/IL extraction systems.
3. Near-**100% extraction efficiency** of mRNA into the hDES phase, including a 2.0-kb FLuc2 and a 4.2-kb SARS-CoV-2 S-2P spike mRNA with clinical modifications (N1-methylpseudouridine, CleanCap, poly(A)).
4. hDES **shields mRNA from RNase A** by exclusion of the enzyme (not by inactivating it), keeping mRNA intact 1 h at 37 °C while aqueous control is fully degraded.
5. **227-day (7.5-month)** room-temperature preservation of intact mRNA vs. complete degradation of the aqueous (0.1 M Tris, pH 7) control.
6. Improved recovery: chaotropic sodium perchlorate raises back-extraction to ~70% (vs ~17% with NaCl; vs 1–22% for prior heavy-metal IL systems).

## 3. Methodology and Architecture
- **hDES composition**: 1-decanol (hydrogen-bond donor) + methyltrioctylammonium chloride / MTAC (HBA, "N8881⁺" cation), optimal molar ratio β = n(1-decanol):n(MTAC) = 2. At β = 2 the phase self-assembles into amphiphilic nanostructures with distinct polar/nonpolar domains; β = 4 → aggregation/precipitation; β ≥ 20 → no extraction.
- **Extraction mechanism**: mRNA complexes with cationic MTAC and partitions into the nanostructured hDES phase. Governed by mRNA charge/conformation, tuned by pH and ionic strength → four regimes: turbid (precipitation), extraction (~100%), mRNA–MTAC membrane, and no extraction.
- **Operating window** aligns with biomanufacturing buffers: Tris 50–100 mM neutral pH (used in Spikevax) and acetate 100 mM pH 5 (LNP encapsulation).
- **Recovery (back-extraction)**: high-ionic-strength buffer screens mRNA–MTAC attraction. 0.1 M Tris pH 7 + 0.37 M NaCl → ~17%; substituting 0.37 M NaClO₄ (chaotrope) → ~70%.
- **Integrity assays**: capillary gel electrophoresis (Bioanalyzer pseudogel + electropherogram); in vitro FLuc2 bioluminescence after transfection into HEK293 cells.
- **RNase challenge**: RNase A (model nuclease, pI 9.6) partitioning measured pH 4–9; mRNA-enriched hDES exposed to RNase A at pH 7 vs pH 9.
  - **RNase A amounts used** (from Methods): stock **RNase A 100 mg/mL (7000 units/mL, QIAGEN)**; conc. conversion uses extinction coeff. 0.71 mL·mg⁻¹·cm⁻¹.
  - *Partition assay*: stock diluted into acetate/Tris 0.1 M buffer, pH 4–9; 500 µL RNase A solution vortexed with 200 µL 1-decanol:MTAC.
  - *mRNA-protection (Fig. 5)*: final RNase A exposure concentration **0.005 µg/mL at pH 9** and **0.01 µg/mL at pH 7** (37 °C, 1 h). RNase-rich hDES prepared at 0.305 µg/mL (~12% partition); aqueous control got 1 µL of 1.50 µg/mL → final 0.005 µg/mL.
  - *hDES-activity test at pH 6*: 0.01 µg/mL RNase A vortexed directly with mRNA-rich hDES; inactivated afterward with RNasin (40 U/µL, 4 µL).
  - So actual mRNA-challenge concentrations are very low (**0.005–0.01 µg/mL**); the 100 mg/mL is only the purchased stock.
- **Long-term storage**: FLuc mRNA in nuclease-free water (0.1 M Tris pH 7) vs 1-decanol:MTAC, room temperature, dark, sampled at day 4 and day 227.

## 4. Key Results and Benchmarks
| Metric | Result |
|---|---|
| Extraction efficiency | ~100% (FLuc 1.6–4.2 kb, capped/modified incl. SARS-CoV-2 spike) |
| Back-extraction (NaCl, 0.37 M) | ~17% |
| Back-extraction (NaClO₄, 0.37 M) | ~70% (prior heavy-metal IL: 1–22%) |
| RNase A partitioning into hDES | 0% below pH 6.5; ~13% at pH 9 |
| RNase protection (pH 7, 37 °C, 1 h) | mRNA intact in hDES; aqueous control fully degraded |
| Room-temp shelf life | ≥227 days intact in hDES; aqueous control degraded by day 227 |
| In vitro activity | Recovered mRNA matches control bioluminescence (HEK293) |
| Viscosity change on water uptake | 447 cP → 85 cP |

- **RNase protection is by exclusion**: at pH 7 (below RNase A pI), the enzyme cannot partition into hDES, so it never contacts the mRNA. At pH 9 the enzyme does partition and *fully degrades* the mRNA (and is even more active in hDES) — so protection requires pH below the nuclease pI. Most RNases have high pI (e.g., skin RNase 7, pI 10.5), so the strategy generalizes at physiological/acidic pH.

## 5. Limitations and Future Work
- Preprint; not peer-reviewed.
- Back-extraction recovery (~70% best case) still leaves room for loss; recovery and precipitation regimes overlap for long mRNA.
- Protection fails at basic pH (≥9) where RNase partitions into the hDES — only valid below nuclease pI.
- MTAC and 1-decanol co-partition into the aqueous phase; downstream removal/purification for therapeutic use not fully addressed.
- Single storage endpoint characterized (day 4 and day 227); degradation kinetics between points not mapped.
- Authors propose an added drying step and use as a shelf-stable non-aqueous precursor to cationic emulsions / LNPs — not yet demonstrated.

## 6. Related Work
- Contrasts with **dry-state** RNA preservation (GenTegraRNA, RNAshell, lyophilization): hDES keeps mRNA in a non-aqueous liquid phase rather than removing water entirely.
- Prior IL/DES RNA extraction (ATPS, magnetic NiCl₂-hDES) used toxic heavy metals and short/yeast model RNAs without integrity validation.
- Complements aqueous **ionic-liquid** RNA storage (choline-based, self-buffering): pedro-2018, de-silva-2026, taha-2015 — but here the medium is *hydrophobic and non-aqueous*, protecting by phase exclusion of water and RNase.
- NADES room-temperature mRNA storage (alfuhaid-2025) and DES-based RNA preservation (kim-2022) are the closest precedents; this work extends the concept to full-length mRNA and explicit RNase shielding.
- Relevant to cold-chain-free mRNA vaccine/therapeutic logistics (oude-blenke-2022, zhang-2026).

## 7. Glossary
- **hDES (hydrophobic deep eutectic solvent)**: water-immiscible eutectic mixture of a hydrophobic hydrogen-bond donor + acceptor; low melting point, low volatility, biodegradable.
- **MTAC / N8881⁺**: methyltrioctylammonium chloride; quaternary-ammonium HBA providing the cationic charge that complexes mRNA.
- **1-decanol**: long-chain fatty alcohol; hydrogen-bond donor providing the hydrophobic environment.
- **β (molar ratio)**: n(1-decanol) : n(MTAC); β = 2 optimal for extraction.
- **ATPS (aqueous two-phase system)**: ternary salt/polymer phase-separation system used in prior RNA extraction; does not protect against RNases.
- **Chaotrope / kosmotrope**: solutes that disrupt (chaotrope, e.g. ClO₄⁻) or stabilize (kosmotrope, e.g. quaternary ammonium) water structure; used here to "salt-in" mRNA for recovery.
- **Back-extraction**: releasing mRNA from the hDES phase into an aqueous recovery buffer.
- **FLuc2 mRNA**: firefly luciferase 2 mRNA, a bioluminescent reporter for translatability.
