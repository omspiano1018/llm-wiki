---
title: "Cholinium-based Good's buffers ionic liquids as remarkable stabilizers and recyclable preservation media for recombinant small RNAs"
authors: Augusto Q. Pedro, Patrícia Pereira, Maria J. Quental, André P. Carvalho, Sérgio M. Santos, João A. Queiroz, Fani Sousa, Mara G. Freire
year: 2018
doi: 10.1021/acssuschemeng.8b03900
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/pedro-2018-cholinium-based-goods-buffers.pdf
pdf_filename: pedro-2018-cholinium-based-goods-buffers.pdf
source_collection: external
---

## One-line Summary
Self-buffering cholinium Good's buffer ionic liquids (GB-ILs) at 20–50% (w/w) raise RNA melting temperature by 14°C and maintain recombinant small RNA integrity for ≥30 days at ambient temperature without freezing.

## 1. Document Information
- **Journal**: ACS Sustainable Chemistry & Engineering (2018, Just Accepted, DOI: 10.1021/acssuschemeng.8b03900)
- **Institutions**: CICECO – University of Aveiro (Freire lab); CICS-UBI – Universidade da Beira Interior (Sousa lab); ITQB-NOVA, Lisbon
- **Published online**: 2018-11-08

## 2. Key Contributions
- First demonstration of cholinium Good's buffer ILs (GB-ILs) as RNA preservation media
- **14°C increase in RNA melting temperature** — highest enhancement reported with ILs at the time
- RNA stable for **≥30 days at both 25°C and 4°C** without freezing (vs. typical −80°C requirement)
- **No cytotoxicity** in two human cell lines at 20% (w/w) concentration
- Molecular dynamics (MD) simulations provide mechanistic insight into ion–RNA interactions
- RNA successfully recovered from IL solutions; ILs recycled and reused

## 3. Methodology and Architecture

### RNA model
Recombinant *Escherichia coli* DH5α / plasmid **pBHSR1-RM** sRNA fraction containing **3 RNA species**, co-produced in vivo and isolated together by acid guanidinium thiocyanate-phenol-chloroform extraction:
1. **tRNA** (transfer RNA) — housekeeping sRNA
2. **pre-miR-29b** (human microRNA precursor) — biopharmaceutical target
3. **6S RNA** — bacterial RNA polymerase regulatory ncRNA

For **MD simulations**, a separate 20-mer linear single-stranded RNA (sequence: AGCGAACGCAUCUCGAGUUC) was used as a computational model.

### IL synthesis
Neutralization of cholinium hydroxide with Good's buffer acids:
- **MES** (2-(N-morpholino)ethanesulfonic acid)
- **TES** (2-[(2-hydroxy-1,1-bis(hydroxymethyl)ethyl)amino]ethanesulfonic acid)
- **HEPES** (2-[4-(2-hydroxyethyl)piperazin-1-yl]ethanesulfonic acid)
- **Tricine** (N-[tris(hydroxymethyl)methyl]glycine)

Concentrations tested: **20% and 50% (w/w)** in aqueous solution.

### Measured pH of the IL solutions (Table S1, 25 °C)
All GB-ILs are **alkaline** (not neutral); only buffered [Ch][DHP] is neutral.

| Ionic Liquid | 20% (w/w) | 50% (w/w) |
|---|---|---|
| [Ch][MES] | 11.29 | 12.38 |
| [Ch][Tricine] | 9.76 | 10.13 |
| [Ch][HEPES] | 9.26 | 9.53 |
| [Ch][TES] | 8.62 | 8.92 |
| Non-buffered [Ch][DHP] | 3.54 | 4.17 |
| Buffered [Ch][DHP] | 7.00 | 7.10 |

The paper states GB-IL solutions span **pH 8.62–12.38** and concludes that "alkaline solutions are beneficial to maintain RNA integrity" and that stability "is enhanced at neutral to alkaline pH values." Only the **acidic** non-buffered [Ch][DHP] (pH < 4.2) impaired RNA; neutralizing it to pH 7 restored protection.

### Characterization methods
- **CD spectroscopy**: RNA secondary structure stability
- **Tm (melting temperature)**: UV melting curves
- **Gel electrophoresis**: structural integrity
- **Zeta potential**: surface charge of RNA–IL complexes
- **MTT assay**: cytotoxicity in human cell lines
- **MD simulations**: ion distribution around RNA chain

### RNA amounts used per assay (verbatim from paper / SI)
The paper does not report a total RNA mass; it specifies RNA **concentration / loading** per assay:

| Assay | RNA concentration / loading | Conditions | Location |
|---|---|---|---|
| CD spectroscopy + Tm (UV melting) | **150 µg/mL** | 1 mm quartz cell; also used for stability incubations | Main text, Methods (Tm) |
| Stability study | **150 µg/mL** | incubation periods 1 h / 15 d / 30 d at 25 °C and 4 °C | Main text, Methods (Tm) |
| Zeta potential (DLS) | **200 µg/mL** | incubated 1 h at 4 °C; mean of 3 independent samples | Main text, Methods (Zeta potential) |
| Agarose gel electrophoresis | **48 µg / lane** (20 µL load) | 0.8% agarose | Supporting Information (Electrophoretic analysis) |

> "Total RNA concentration was 150 µg/mL, and distinct incubation periods and temperatures of sRNA with ILs were performed." (Tm method)
> "...the total RNA concentration was 200 µg/mL." (Zeta potential method)
> "20 µL of sRNA corresponding to 48 µg was analyzed by horizontal electrophoresis using 0.8% of agarose gel." (SI)

### Recyclability protocol
RNA precipitated from IL solution → IL recovered → filtered → reused for next stabilization cycle.

## 4. Key Results and Benchmarks
- **Tm increase**: up to +14°C compared to buffer alone (highest IL-mediated Tm increase reported)
- **30-day stability**: most GB-ILs maintain RNA integrity at 25°C and 4°C without freezing
- **Zeta potential**: IL anions alter overall charge of RNA first solvation sphere; IL cation count similar across ILs but anion distribution differs
- **Cytotoxicity**: no significant toxicity at 20% (w/w) in two human cell lines
- **MD insight**: cholinium cations surround RNA uniformly; Good's buffer anions modulate the hydration shell and electrostatic environment, reducing hydrolytic stress
- **Recovery & recycling**: RNA recovered with intact structure; ILs reused without performance loss

## 5. Limitations and Future Work
- Tested only on recombinant sRNA (pre-miR-29); generalizability to longer/more complex RNA not shown
- Only four Good's buffer anions tested; broader IL space not explored
- Long-term stability beyond 30 days not characterized
- In vivo/animal model data not included
- Higher concentrations (50% w/w) may limit downstream compatibility

## 6. Related Work
- Cholinium dihydrogen phosphate for siRNA stabilization (earlier IL RNA work)
- Imidazolium/tetraalkylammonium GB-ILs for protein stabilization (same group, ref [30/31])
- Cholinium chloride established as low-toxicity, biodegradable cation
- De Silva et al. 2026 extends this concept to complex plant RNA (→ [[computational/de-silva-2026-a-biocompatible-and-recyclable]])
- Yu et al. 2026 uses choline-amino acid ILs for LNP-mediated mRNA delivery (→ [[computational/yu-2026-ionic-liquids-as-alternative]])

## 7. Glossary
- **GB-IL (Good's Buffer Ionic Liquid)**: IL formed from cholinium cation and a Good's buffer anion (MES, HEPES, TES, Tricine); self-buffering property
- **Good's buffers**: biological buffers (e.g., HEPES, MES) chosen for minimal interference with biochemical reactions
- **pre-miR-29**: microRNA precursor; processed in vivo into mature miR-29 which regulates fibrosis, apoptosis pathways
- **Tm (melting temperature)**: temperature at which 50% of RNA double-stranded structure unfolds; higher = more stable
- **Zeta potential**: measure of electrostatic charge at particle surface; reflects colloidal stability
- **MD simulation**: molecular dynamics; computational method to simulate atomic/molecular motion over time
- **sRNA**: small RNA; RNA molecules typically <200 nt involved in gene regulation
