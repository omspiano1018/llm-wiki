---
title: "Non-Invasive Transdermal Delivery of Antisense Oligonucleotides with Biocompatible Ionic Liquids"
authors: Kiyohiro Toyofuku, Rie Wakabayashi, Noriho Kamiya, Masahiro Goto
year: 2023
doi: 10.1021/acsami.3c03900
source: toyofuku-2023-non-invasive-transdermal-delivery-of.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/toyofuku-2023-non-invasive-transdermal-delivery-of.pdf
pdf_filename: toyofuku-2023-non-invasive-transdermal-delivery-of.pdf
source_collection: external
tags: [ionic-liquid, LBIL, EDMPC, transdermal-delivery, antisense-oligonucleotide, ASO, solid-in-oil, trabedersen, TGF-beta2, skin-penetration, Goto-group]
---

## Summary
Toyofuku et al. (Goto group, Kyushu University) build a **needle-free** delivery system for antisense oligonucleotides (ASOs). The trick is a **solid-in-oil (S/O) dispersion** in which the hydrophobic surfactant coating the drug is a **lipid-based ionic liquid (LBIL)**, [EDMPC][fatty acid]. This single formulation solves the two barriers that had never been crossed together: (1) getting a large, hydrophilic, polyanionic nucleic acid through the **stratum corneum** (which normally blocks anything >500 Da), and (2) getting it across the negatively charged **cell membrane** into the cytoplasm where it can act. Using the ASO **Trabedersen** (anti-TGF-β2), the IL-S/O patch silenced TGF-β2 and suppressed melanoma in mice **as well as injection — without a needle**.

## Key Contributions
- **First dual-barrier carrier**: to the authors' knowledge, no prior carrier achieved *both* transdermal and intracellular delivery of a nucleic acid drug. IL-S/O does both at once.
- **IL as surfactant, not solvent**: replaces the nonionic surfactant of classic S/O with a charged LBIL. Because the zwitterionic/cationic IL binds the polyanionic ASO electrostatically, the drug–IL complex **stays intact after crossing the SC** (nonionic surfactants dissociate and drop the drug at the SC).
- **Anion structure–activity relationship**: skin permeation ranks **Lin > Ole > Ste**, matching the number of *cis* double bonds in the C18 fatty-acid anion, which is what disrupts the SC lipid lamellae (FT-IR CH₂ blue shift 1–3 cm⁻¹).
- **Beats a commercial reagent**: [EDMPC][Lin]-S/O gives higher cellular uptake and stronger TGF-β2 knockdown than Oligofectamine in B16F10 cells.
- **In vivo equivalence to injection**: transdermal patch matches subcutaneous injection for antitumor effect, with no significant toxicity or weight loss.

## Methodology and Architecture
- **LBIL** = **[EDMPC][fatty acid]**: cationic ethylated phospholipid EDMPC + a C18 fatty-acid anion (linoleate/oleate/stearate). Made by O-ethylating DMPC, exchanging to chloride with 0.2 N HCl, then equimolar neutralization with the fatty acid — the Goto-group platform from [[computational/uddin-2020-lipid-based-biocompatible-ionic-liquids]].
- **IL-S/O build**: homogenize aqueous Trabedersen with LBIL-in-cyclohexane → freeze-dry to an IL–ASO complex at a **1:30 weight ratio** (ASO:IL, needed for a stable dispersion) → redisperse in **isopropyl myristate** oil. Particles ~161 nm, spherical, stable ≥28 days.
- **Assays**: Franz-cell skin permeation (mouse / Yucatan micropig, CLSM + HPLC); dual-label CLSM (Cy5-ASO + NBD-IL) to prove co-penetration as an intact complex; FT-IR of stratum-corneum sheets for lamellar disruption; B16/B16F10 melanoma uptake (flow cytometry) and TGF-β2 ELISA; B16F10 tumor-bearing mice, injection vs transdermal patch (300 µg/mouse).

## Results
- **Skin penetration**: [EDMPC][Lin]-S/O drives Trabedersen deep into the epidermis (strong CLSM signal past the SC) and delivers far more than aqueous PBS or the chloride-salt [EDMPC][Cl]-S/O control. Ranking Lin > Ole > Ste.
- **Mechanism**: red (ASO) and green (IL) fluorescence co-localize below the SC → the ASO and IL travel together as a complex, not dissociated. FT-IR blue shifts confirm the IL perturbs the SC lipid lamellae, most strongly with the doubly-unsaturated linoleate.
- **Cellular uptake & antisense**: IL-S/O > Oligofectamine > PBS for uptake; TGF-β2 expression significantly reduced by IL-S/O (IL alone has no effect → the effect is a genuine antisense action of the delivered ASO).
- **In vivo**: transdermal IL-S/O patch suppresses B16F10 tumor growth comparably to injection despite delivering less total ASO; TGF-β2 in tumor is significantly reduced; negligible cytotoxicity, no weight change.
- **Generalizable**: authors propose the same IL-S/O approach should extend to siRNA and mRNA (not demonstrated here).

## Related Papers
- [[computational/uddin-2020-lipid-based-biocompatible-ionic-liquids]] — founding synthesis and characterization of the [EDMPC][fatty acid] LBIL platform this paper applies to ASO delivery.
- [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] — same group applying [EDMPC][Lin]-type LBILs to **mRNA** intracellular delivery (the lipid itself is the IL).
- [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]] — ionic liquids as a class for transdermal delivery (CAGE origin).
- [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]] — 10-year review of CAGE IL transdermal/oral delivery.
- [[computational/egorova-2021-ionic-liquids-prospects-for-nucleic]] — foundational review of ILs for nucleic-acid handling and delivery (cationic head + lipophilic tail SAR).
- [[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]] — review of ILs as biocompatible carriers for DNA/siRNA/mRNA/ASO.
