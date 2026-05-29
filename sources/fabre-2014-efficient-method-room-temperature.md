---
title: "An Efficient Method for Long-Term Room Temperature Storage of RNA"
authors: Anne-Lise Fabre, Marthe Colotte, Aurelie Luis, Sophie Tuffet, Jacques Bonnet
year: 2014
doi: 10.1038/ejhg.2013.145
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/An efficient method for long-term room temperature storage of RNA.pdf
pdf_filename: An efficient method for long-term room temperature storage of RNA.pdf
source_collection: external
---

## One-line Summary
Original Imagene study demonstrating long-term room temperature storage of RNA in vacuum-dried stainless steel minicapsules under anhydrous and anoxic atmosphere, with quantitative Arrhenius lifetime prediction showing RNA can survive centuries in dry state.

## 1. Document Information
- **Title**: An Efficient Method for Long-Term Room Temperature Storage of RNA
- **Authors**: Anne-Lise Fabre, Marthe Colotte, Aurelie Luis, Sophie Tuffet, Jacques Bonnet
- **Year**: 2014 (published online 17 July 2013)
- **Journal**: European Journal of Human Genetics, vol. 22, pp. 379-385
- **DOI**: 10.1038/ejhg.2013.145
- **Affiliations**: Imagene (R&D, Universite de Bordeaux 2, ENSTBB; Production Platform, Evry); Institut Bergonie (U916, Bordeaux); Universite de Bordeaux-Victor Segalen

## 2. Key Contributions
- First quantitative estimation of RNA lifetime under controlled dry, anhydrous, anoxic conditions
- Demonstrates that atmospheric humidity is the major deleterious factor for solid-state RNA degradation
- Establishes Arrhenius degradation model: activation energy (Ea) = 28.5 kcal/mol; room temperature degradation rate = 3.2×10^-13/nt/s (95% CI: 2.3–4.2/nt/s)
- Predicts that in these conditions, an RNA molecule will experience 0.7–1.3 cuts per 1000 nucleotides per century
- Shows that stored RNA is compatible with downstream analyses (RT-qPCR); no significant change in Cq values over simulated decades
- Demonstrates sequence-independent degradation rate in solid state

## 3. Methodology and Architecture
- RNA sources: 3,313 nt mRNA (yeast β-galactosidase, HPLC-purified, Mitoprod); human total RNA from HeLa cells; bacterial total RNA from E. coli
- RNA suspended in water, TE buffer, or Tris buffer to introduce variability
- Encapsulation: 2 µg RNA + Imagene proprietary stabilizer → 0.2 mL glass insert in stainless steel minicapsule → vacuum-dried → laser-welded under anhydrous argon
- Accelerated degradation: heating at 50–130°C; for humidity effect: opened capsules in ~50% relative humidity atmosphere
- RNA quality analysis: capillary electrophoresis (Agilent Bioanalyzer, RNA 6000 nano kit); agarose gel electrophoresis (quantitative fluorescence); bands of interest: 28S (5070 nt), 23S (2904 nt), mRNA (3313 nt)
- Proportion of intact phosphodiester bonds calculated by normalizing to t0 fluorescence, corrected for molecule size
- RT-qPCR: reverse transcription followed by quantitative PCR to assess functional RNA quality

## 4. Key Results and Benchmarks
- Atmospheric humidity restoration of opened capsules restores initial instability even in solid state — moisture is rate-limiting degradation factor
- Degradation rates proportional to RNA molecule length — sequence-independent in solid state
- Arrhenius model fit: Ea = 28.5 kcal/mol; predicted RT degradation rate 3.2×10^-13/nt/s
- At RT: 0.7–1.3 cuts per 1000 nt per century → effectively minimal degradation over human-scale timescales
- No significant change in RT-qPCR Cq values over simulated period of several decades
- Method superior to existing commercial room-temperature RNA storage approaches: hydrophilic matrices cannot protect from atmospheric water; FTA paper limited for RNA; adsorption-on-substrate method unvalidated
- RNA quality maintained for multiple RNA species (mRNA, rRNA) and preparations (water, TE, Tris buffer)

## 5. Limitations and Future Work
- Proprietary stabilization solution composition not disclosed; limits replication by independent labs
- Laser welding under argon requires specialized Imagene equipment
- Only tested mRNA, rRNA species; compatibility with other RNA types (tRNA, lncRNA, miRNA) not fully characterized
- RT-qPCR compatibility demonstrated; compatibility with RNA-seq, microarrays, and other high-throughput assays not fully validated in this paper
- Long-term validation at actual room temperature (not accelerated) ongoing but decades-long studies not yet complete

## 6. Related Work
- Colotte et al. (2023): application of same technology to SARS-CoV-2 diagnostic RNA controls
- Imagene prior DNA storage publications (Bonnet group): same capsule technology applied to DNA
- FTA paper technology: comparison matrix for RNA storage (manuscript concludes FTA is limited)
- Biomatrica RNAstable, IntegenX GenTegra RNA: commercial matrix alternatives not providing full atmosphere exclusion
- Lou et al. (2014): concurrent review of room temperature biospecimen storage options citing this work

## 7. Glossary
- **Anhydrous atmosphere**: Atmosphere with essentially no water vapor; critical for preventing RNA hydrolysis in solid state
- **Anoxic atmosphere**: Oxygen-free atmosphere; prevents RNA oxidative degradation
- **Arrhenius model**: Kinetic model relating reaction rate constant k to temperature T via k = A·exp(-Ea/RT); used to extrapolate RT stability from elevated temperature experiments
- **Activation energy (Ea)**: Energy barrier for RNA degradation reaction; 28.5 kcal/mol measured for this system
- **RNase-free**: Designation for solutions, glassware, or conditions in which ribonuclease activity is absent
- **Cq value (cycle threshold)**: RT-qPCR metric; cycle number at which fluorescence crosses threshold; lower = more RNA; stability of Cq indicates stable RNA
- **Capillary electrophoresis (Bioanalyzer)**: Agilent platform for RNA quality assessment; provides RIN (RNA Integrity Number) and electropherogram
- **Laser welding**: Hermetic sealing of metallic capsules using laser; ensures anhydrous and anoxic environment
