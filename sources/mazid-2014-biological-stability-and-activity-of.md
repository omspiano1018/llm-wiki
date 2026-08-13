---
title: "Biological Stability and Activity of siRNA in Ionic Liquids"
authors: Rowshon R. Mazid, Umaporn Divisekera, Wenrong Yang, Ranganathan Vijayaraghavan, Douglas R. MacFarlane, Christina Cortez-Jugo, Wenlong Cheng
year: 2014
doi: 10.1039/C4CC05086J
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/mazid-2014-biological-stability-and-activity-of.pdf
pdf_filename: mazid-2014-biological-stability-and-activity-of.pdf
source_collection: external
---

## One-line Summary
Storing siRNA in hydrated choline dihydrogen phosphate (CDP) ionic liquid dramatically slows RNase A degradation — extending shelf life from minutes/hours to up to three months — while the recovered siRNA remains active and knocks down eGFP in HeLa cells, pointing to ILs as room-temperature, refrigeration-free siRNA storage buffers.

## 1. Document Information
- **Type**: Communication (peer-reviewed Accepted Manuscript), *Chemical Communications* (ChemComm), Royal Society of Chemistry
- **Published**: 05 September 2014; 5 pages
- **Institutions**: Monash University, Clayton VIC, Australia — Dept. of Chemical Engineering (Cheng group); School of Chemistry (MacFarlane group); Dept. of Mechanical & Aerospace Engineering
- **Funding**: Australian Research Council Discovery Projects DP120100170, DP120100835; ARC Super Science Fellowship FS100100073

## 2. Key Contributions
1. **First report** of siRNA stability in an ionic liquid (no prior report of siRNA-in-IL existed).
2. Hydrated **choline dihydrogen phosphate (CDP) IL** substantially prolongs siRNA shelf life in the presence of RNase A — up to **three months**, vs. complete degradation in PBS within **0.5 h**.
3. IL-stored siRNA **remains biologically active**: eGFP siRNA induces clear gene knockdown in eGFP-expressing HeLa cells even after RNase A challenge.
4. Demonstrates enhanced **structural (CD spectroscopy), thermal (higher Tm, more negative ΔG°₂₅), and biological** stability simultaneously.
5. CDP IL is **low-cytotoxicity/biocompatible** at the tested concentrations — no need to remove IL before biological testing.
6. Proposes ILs as **next-generation biobuffers** eliminating lyophilization/refrigeration for siRNA storage and transport.

## 3. Methodology and Architecture
- **IL system**: choline dihydrogen phosphate (CDP), hydrated, tested at **20% (w/w)** and **50% (w/w)** in water; buffered near the H₂PO₄⁻/HPO₄²⁻ region (~pH 7). Compared against 0.01 M PBS control.
- **siRNAs**: CD45 siRNA and eGFP siRNA (double-stranded, ~21mer).
- **Nuclease challenge**: RNase A at 0.25–2 mg/mL; incubation initiated at 37 °C, then samples stored at ambient temperature for time-lapse studies.
- **Assays**:
  - **Native + denaturing (urea) PAGE gel electrophoresis** — track dsRNA (upper band) vs ssRNA (lower band); denaturing gel vs 21mer ssRNA size marker confirms band identity.
  - **Circular dichroism (CD) spectroscopy** — A-type dsRNA signature (positive Cotton band ~268 nm, crossover ~240 nm) before/after RNase A.
  - **UV thermal melting** — Tm and van't Hoff two-state thermodynamics (ΔH°, TΔS°, ΔG°₂₅), Cary UV Thermal software, 1 µM strand.
  - **Flow cytometry** — eGFP fluorescence of live HeLa cells to quantify knockdown (geometric mean); Lipofectamine RNAiMAX transfection.
  - **alamarBlue viability assay** — cytotoxicity, normalized to untreated cells.
- **Proposed degradation mechanism in CDP IL** (two steps, slowed by high ionic strength): (1) RNase A destabilizes/de-winds dsRNA by binding ssRNA; (2) RNase A catalyzes P–O bond cleavage of the RNA strand. High ionic strength retards step 1, giving co-existing ds- and ss-siRNA bands.

## 4. Key Results and Benchmarks
| Metric | PBS | 20% (w/w) CDP IL | 50% (w/w) CDP IL |
|---|---|---|---|
| siRNA gel bands after RNase A | fully degraded in **0.5 h** | clear bands at 4 h | clear bands at 4 h |
| Time to fully degrade siRNA (2 mg/mL RNase A) | — | ~14 days | ~24 days |
| Time to fully degrade (1 mg/mL RNase A) | — | ~50 days | ~77 days |
| Time to fully degrade (0.25 mg/mL RNase A) | — | — | ~4 months |
| Melting temperature Tm (eGFP siRNA, 1 µM) | 61.5 °C | 65.8 °C | 70.2 °C |
| ΔG°₂₅ (kcal/mol) | −16.8 ± 0.2 | −23.2 ± 0.5 | −30.5 ± 0.4 |
| Knockdown, **no** RNase A | 80% | 74% | 80% |
| Knockdown, **with** RNase A | 0% (no knockdown) | 69% | 74% |

- **eGFP siRNA** in 50% IL still showed native-gel bands after **three months** of storage.
- **CD spectra**: slight red shift of the crossover point in ILs (more pronounced at 50%); dsRNA A-type structure preserved after RNase A in IL but lost in PBS.
- **Cytotoxicity**: negligible difference between IL- and PBS-treated cells; no observable difference between 20% and 50% IL — knockdown is siRNA-specific, not cell death.
- More negative ΔG°₂₅ and higher Tm with increasing IL fraction → thermodynamically more stable duplex.

## 5. Limitations and Future Work
- **Single nuclease** (RNase A) tested; authors flag testing other RNases and serum as future work.
- Only CDP IL at two concentrations; no broad IL panel.
- Mechanism (de-winding retardation by high ionic strength) is inferred from band patterns/CD, not directly resolved.
- No in vivo delivery or therapeutic demonstration — activity shown only in cultured HeLa cells with Lipofectamine transfection.
- Short communication; limited kinetic sampling between time-lapse endpoints.

## 6. Related Work
- Builds on CDP IL biocompatibility and stabilization of **DNA** (Vijayaraghavan 2010; Tateishi-Karimata 2014) and **proteins** (cytochrome c, lipases — Fujita, Weaver, Vrikkis, Foureau) near the phosphate buffer region ~pH 7.
- CDP IL previously stabilized an **entire tobacco virus** (Byrne 2012).
- Low-cytotoxicity/biocompatibility of hydrated CDP established by Weaver 2010 (Green Chem.).
- Foundational within this wiki's **choline-based IL RNA/nucleic-acid** thread: cholinium Good's-buffer ILs raising RNA Tm (pedro-2018), choline-glutamate plant-RNA stabilization (de-silva-2026), and IL/DES nucleic-acid biopharmaceutical reviews (verissimo-2026, egorova-2021, mirhadi-2024).
- Complements the RNase-shielding-by-phase-exclusion mechanism of the hydrophobic DES work (dinh-2025) — here protection is instead by high ionic strength slowing enzymatic de-winding in an *aqueous* IL.

## 7. Glossary
- **siRNA (small interfering RNA)**: 20–25 bp double-stranded RNA that silences gene expression via the RNAi pathway by directing cleavage of complementary mRNA.
- **CDP (choline dihydrogen phosphate)**: biocompatible ionic liquid; choline cation + dihydrogen phosphate anion; buffers near the H₂PO₄⁻/HPO₄²⁻ region (~pH 7).
- **RNase A**: ubiquitous nuclease that cleaves the P–O bond of single-stranded RNA; primary degradation threat to siRNA.
- **CD45 / eGFP siRNA**: model siRNAs targeting the CD45 phosphatase and enhanced green fluorescent protein reporter, respectively.
- **van't Hoff two-state model**: thermodynamic analysis of duplex melting yielding ΔH°, ΔS°, ΔG° from the UV melting curve.
- **A-type RNA structure**: canonical dsRNA helix conformation; CD signature = positive band ~268 nm, crossover ~240 nm.
- **Knockdown efficiency**: reduction in target-protein (eGFP) fluorescence after siRNA transfection, here from flow-cytometry geometric mean.
