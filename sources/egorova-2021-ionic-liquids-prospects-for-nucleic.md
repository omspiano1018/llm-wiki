---
title: "Ionic liquids: prospects for nucleic acid handling and delivery"
authors: Ksenia S. Egorova, Alexandra V. Posvyatenko, Sergey S. Larin, Valentine P. Ananikov
year: 2021
doi: 10.1093/nar/gkaa1280
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/egorova-2021-ionic-liquids-prospects-for-nucleic.pdf
pdf_filename: egorova-2021-ionic-liquids-prospects-for-nucleic.pdf
source_collection: external
---

## One-line Summary
Comprehensive Nucleic Acids Research "Survey and Summary" review of how nucleic acids behave in ionic-liquid media and how ILs can be exploited for nucleic acid handling, storage, extraction, and — most relevant to therapeutics — intracellular gene delivery, with a curated table of every IL gene-delivery study reported up to 2021.

## 1. Document Information
- **Title**: Ionic liquids: prospects for nucleic acid handling and delivery
- **Authors**: Ksenia S. Egorova, Alexandra V. Posvyatenko, Sergey S. Larin, Valentine P. Ananikov
- **Year**: 2021
- **Journal**: Nucleic Acids Research, vol. 49, no. 3, pp. 1201–1234
- **DOI**: 10.1093/nar/gkaa1280
- **Affiliations**: Zelinsky Institute of Organic Chemistry (RAS); Dmitry Rogachev National Medical Research Center of Pediatric Hematology, Oncology and Immunology, Moscow
- **Type**: Review (Survey and Summary; open access CC BY-NC)

## 2. Key Contributions
- Authoritative, mechanism-first review bridging two communities: IL physical chemistry and nucleic-acid/gene-therapy delivery
- Frames ILs as **tunable hierarchical (micro-/nano-structuring) media** — "jigsaw-puzzle" molecules with ~10^18 possible ion combinations — and connects this structuring to nucleic-acid stabilization and membrane translocation
- Systematically tabulates the IL **gene-delivery** literature (Table 6): simple ILs, cationic amphiphiles, Gemini surfactants, poly(ILs), and "IL-robed" (self-delivering) oligonucleotides
- Articulates the ideal gene-delivery agent criteria (nuclease protection, non-toxic, non-immunogenic, membrane penetration, cargo release) and maps where ILs currently fit (mostly polymer- and lipid-mediated delivery)
- Identifies forward directions: IL-tuned nanoparticles, cell-penetrating peptides (ε-poly-L-lysine in ammonium ILs), virus-like particles

## 3. Methodology and Architecture
Three-part narrative review:
1. **ILs as tunable hierarchical systems** — structural levels (covalent skeleton, replaceable side chains, Coulomb / π–π / van der Waals / H-bonds) giving rise to nano/micro structuring; behaviour of nucleic acids in IL and IL–water media (duplex/triplex/G-quadruplex stabilization, hydration, water activity).
2. **Survey of nucleic-acid delivery techniques** — physical methods, non-viral (polymers, liposomes/lipofection, "self-delivering" oligonucleotides), and viral systems — establishing the context ILs must compete in.
3. **IL application in delivery** — compound-class-by-class analysis with Table 6 (the practical core for a delivery developer).

## 4. Key Results and Benchmarks
From Table 6 (representative IL gene-delivery systems):
- **[C4Mim][PF6] + pDNA (eGFP)**: IL forms nanostructures with pDNA via electrostatic interaction with phosphate groups; protects pDNA against up to 120 min ultrasonication; co-formulation with Lipofectamine **enhances transfection** in COS-7, HEK293, HeLa with low cytotoxicity.
- **CAGE (cholinium geranate) + CAPA (cholinium phenylpropanoate), 25% v/v each + siRNA (GAPDH, NFKBIZ)**: stabilizes siRNA and gives efficient **epidermal siRNA delivery in vivo** (~0.20 nmol·cm⁻²); geranate proposed to drive translocation across the lipid bilayer; no skin inflammation/irritation — proposed for psoriasis.
- **bis(alkoxy)benzyl imidazolium halides (C6–C18) + siRNA (luciferase)**: with DOPE, 1mM C12 derivative:2mM DOPE at 10 nM gives knockdown comparable to Lipofectamine 2000; complex formation depends on **alkyl chain length** (anion has no effect); ~70 nm complexes with **positive zeta potential** → cell-surface binding + endocytosis.
- **Dicationic imidazolium IL in DPPC:DOPE liposomes (20 mol%) + pDNA (GFP)**: efficient HeLa transfection (alkylammonium moiety drives DNA + membrane electrostatics).
- **Double-chained pyridinium amphiphiles + DNA**: clear SAR — longer C18 chain lowers toxicity but also transfection; introducing C18:1 unsaturation raises transfection; two unsaturated chains raise both toxicity and transfection sharply; trans > cis for transfection.

## 5. Limitations and Future Work
- Field was still young in 2021; most IL delivery data are in vitro / proof-of-concept, dominated by polymer- and lipid-mediated formats
- Cytotoxicity tracks the same lipophilicity/chain-length features that drive delivery efficiency (recurring activity–toxicity trade-off)
- Under-explored but promising: IL-tuned nanoparticles, CPP-assisted delivery, virus-like-particle stabilization
- Storage/handling applications (single-cell sequencing, IL-assisted extraction/preconcentration for PCR, sequence-specific extraction, biosensors) are more mature than therapeutic delivery

## 6. Related Work
- Cited heavily for IL–DNA structuring and CAGE-family delivery (Zakrewsky/Mitragotri lineage)
- Conceptual sibling to [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] (later, narrower on biopharmaceutical RNA + DESs)
- Storage angle overlaps with [[computational/pedro-2018-cholinium-based-goods-buffers]] (small-RNA stabilization)

## 7. Glossary
- **IL-robed / self-delivering oligonucleotide**: oligonucleotide converted into an IL form (lipophilic cation paired with the oligo) so it can cross the membrane without a separate vector
- **Gemini surfactant**: dimeric amphiphile with two head groups + two tails joined by a spacer; strong DNA condensation
- **Poly(IL) (PIL)**: polymer with ionic-liquid repeat units
- **Lipofection**: lipid-mediated transfection
- **G-quadruplex**: four-stranded guanine-rich nucleic acid secondary structure; stabilized in some hydrated cholinium ILs
- **DOPE**: dioleoylphosphatidylethanolamine — fusogenic helper lipid used to boost endosomal escape
- **Micro-structuring**: dynamic nano/micro heterogeneity of IL media that underlies their solvent/stabilizing behaviour
