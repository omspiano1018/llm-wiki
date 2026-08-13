---
title: "Non-Invasive Transdermal Delivery of Antisense Oligonucleotides with Biocompatible Ionic Liquids"
authors: Kiyohiro Toyofuku, Rie Wakabayashi, Noriho Kamiya, Masahiro Goto
year: 2023
doi: 10.1021/acsami.3c03900
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/toyofuku-2023-non-invasive-transdermal-delivery-of.pdf
pdf_filename: toyofuku-2023-non-invasive-transdermal-delivery-of.pdf
source_collection: external
---

## One-line Summary
A solid-in-oil (S/O) dispersion that uses biocompatible lipid-based ionic liquids (LBILs, [EDMPC][fatty acid]) as the hydrophobic surfactant coats an antisense oligonucleotide (Trabedersen) and achieves *simultaneous* transdermal skin penetration and intracellular delivery, silencing TGF-β2 and inhibiting melanoma growth in mice as effectively as injection — without needles.

## 1. Document Information
- **Type**: Research Article, ACS Applied Materials & Interfaces 2023, 15, 33299–33308 (peer-reviewed)
- **Institution**: Kyushu University (Fukuoka, Japan) — Department of Applied Chemistry; Advanced Transdermal Drug Delivery System Center; Center for Future Chemistry (Masahiro Goto group)
- **Received**: 17 March 2023; Accepted: 21 June 2023; Published: 5 July 2023
- **Funding**: JSPS KAKENHI (JP22K18314, JP21F21051); AMED (22ak0101174h0002)
- **Download date**: 2026-07-16

## 2. Key Contributions
1. First carrier reported to achieve **both** transdermal (across the stratum corneum) **and** intracellular (across the cell membrane) delivery of a nucleic acid drug in a single system.
2. Introduces **IL-S/O**: a solid-in-oil dispersion where lipid-based ionic liquids (LBILs) serve as the *surfactant* coating instead of conventional nonionic surfactants.
3. Uses zwitterionic/cationic **[EDMPC][fatty acid]** LBILs (fatty acid = linoleate Lin, oleate Ole, or stearate Ste) whose electrostatic attraction to the polyanionic ASO keeps the drug–IL complex intact even after skin penetration (unlike nonionic S/O, where surfactant dissociates at the SC).
4. Demonstrates a structure–activity relationship: skin-permeation enhancement follows the number of *cis* double bonds in the anion (Lin > Ole > Ste), correlating with lamellar-lipid disruption measured by FT-IR blue shifts.
5. In vivo proof: transdermal IL-S/O patch matches subcutaneous injection for antitumor effect against B16F10 melanoma despite lower total ASO uptake — and outperforms the commercial transfection reagent Oligofectamine for cellular uptake and TGF-β2 knockdown in vitro.

## 3. Methodology and Architecture
- **LBIL synthesis**: DMPC (phosphatidylcholine) O-ethylated with ethyl trifluoromethanesulfonate (1:1, 45 °C, 12 h, N₂) → EDMPC-triflate; chloride exchange with 0.2 N HCl → EDMPC-Cl; equimolar neutralization with a C18 fatty acid (Lin/Ole/Ste) → [EDMPC][fatty acid], freeze-dried, verified by ¹H NMR (this is the Goto-group LBIL platform from uddin-2020).
- **Model drug**: Trabedersen (AP 12009), a phosphorothioate ASO targeting TGF-β2 mRNA; FAM-, Cy5-, or unlabeled versions used.
- **IL-S/O preparation**: aqueous Trabedersen (1 mg/mL) + LBIL-in-cyclohexane (15 mg/mL) homogenized at 26,000 rpm 2 min → freeze-dried to an IL–Trabedersen complex (1 mg ASO : 30 mg IL, i.e. 1:30 weight ratio needed for stability) → redispersed in isopropyl myristate (IPM) oil. Final ASO = 1.0 mg/mL. Particle size ~153–165 nm (DLS/TEM), stable ≥28 days.
- **Skin permeation**: Franz diffusion cell, hairless mouse / Yucatan micropig skin, 32.5 °C, 6 h; CLSM cross-sections + HPLC quantification.
- **Mechanism probes**: dual-label CLSM (Cy5-ASO + NBD-IL) to test co-penetration; FT-IR of isolated SC sheets (CH₂ stretching at ~2850/2920 cm⁻¹) to measure lamellar disruption.
- **Cellular uptake / antisense**: B16 / B16F10 mouse melanoma; flow cytometry, CLSM; TGF-β2 ELISA; CCK-8 cytotoxicity.
- **In vivo**: B16F10 tumor-bearing C57BL/6N mice; injection vs transdermal patch; dose 300 µg/mouse; tumor volume, ASO accumulation, TGF-β2 expression, body weight.

## 4. Key Results and Benchmarks
| Metric | Result |
|---|---|
| IL-S/O particle size | ~161 nm ([EDMPC][Lin]), spherical (TEM), PDI stable to day 28 |
| Stable weight ratio | 1:30 (ASO : total IL surfactant) required |
| Skin penetration ranking | [EDMPC][Lin] > [EDMPC][Ole] > [EDMPC][Ste] >> [EDMPC][Cl] > PBS |
| FT-IR CH₂ blue shift | 1–3 cm⁻¹ after IL treatment (Lin largest), ∝ number of *cis* double bonds |
| Co-penetration | Cy5-ASO (red) + NBD-IL (green) both reach viable epidermis → deliver as intact complex |
| Cellular uptake | [EDMPC][Lin]-S/O > Oligofectamine > PBS (flow cytometry, B16F10) |
| Antisense (in vitro) | IL-S/O suppresses TGF-β2 more than Oligofectamine; IL-alone has no effect |
| In vivo antitumor | Transdermal IL-S/O patch ≈ injection for tumor suppression; less total ASO but comparable effect |
| Cytotoxicity | Negligible for all three LBILs at working concentrations (CCK-8) |
| Safety | No significant body-weight change, no obvious side effects |

## 5. Limitations and Future Work
- Model ASO only (Trabedersen/TGF-β2); authors state the platform *should* extend to siRNA and mRNA but do not demonstrate it here.
- In vitro skin = mouse/micropig, not human; oil-on-medium cell assay is an approximation of the SC→epidermis transfer, and exact oil-to-medium transfer amount is hard to quantify.
- Mechanism (intact complex crossing the SC via electrostatic ASO–IL binding + lamellar disruption) is inferred from imaging + FT-IR, not directly resolved.
- Long-term storage stability of the loaded formulation and scale-up / regulatory path not addressed.

## 6. Related Work
- **Founding LBIL synthesis**: uddin-2020 — the [EDMPC][fatty acid] platform (synthesis, characterization, biocompatibility) that this paper applies to ASO delivery.
- **Peptide precedent**: Goto group previously used LBILs for transdermal peptide delivery (Uddin 2021, ACS Appl. Bio Mater.); S/O technology for protein/vaccine delivery (Tahara 2008, Wakabayashi 2018).
- **mRNA analogue**: tanaka-2026 — same group, [EDMPC][Lin]-type LBILs complexing mRNA for intracellular delivery (the lipid itself is the IL).
- **IL transdermal / CAGE**: zakrewsky-2014, mitragotri-2024 — ionic liquids as a class for transdermal delivery and pathogen neutralization.
- **IL-for-nucleic-acid context**: egorova-2021 (NAR review), mirhadi-2024, sagitha-2023 — ILs for nucleic-acid handling and delivery.

## 7. Glossary
- **ASO (antisense oligonucleotide)**: short single-stranded nucleic acid that binds a target mRNA by sequence complementarity and blocks its translation.
- **Trabedersen (AP 12009)**: ASO against TGF-β2 mRNA; TGF-β2 is a tumor-promoting cytokine.
- **S/O (solid-in-oil) dispersion**: nanoscale hydrophilic drug particles coated by a hydrophobic surfactant and dispersed in oil, improving penetration of the hydrophobic stratum corneum.
- **IL-S/O**: this work's S/O variant using an ionic liquid as the surfactant.
- **LBIL (lipid-based ionic liquid)**: ionic liquid built from a lipid ion, here EDMPC cation + fatty-acid anion; biocompatible, surface-active, skin-penetration-enhancing.
- **EDMPC**: 1,2-dimyristoyl-sn-glycero-3-ethyl-phosphatidylcholine; the ethylated (cationic) phospholipid used as the IL cation.
- **Lin / Ole / Ste**: linoleate / oleate / stearate — C18 fatty-acid anions with 2 / 1 / 0 *cis* double bonds.
- **Stratum corneum (SC)**: outermost skin layer; hydrophobic lipid-lamellar barrier that normally excludes molecules >500 Da.
- **IPM (isopropyl myristate)**: the oil phase carrying the S/O dispersion.
