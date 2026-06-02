---
title: "Regulation of Translation Initiation in Eukaryotes: Mechanisms and Biological Targets"
authors: Nahum Sonenberg, Alan G. Hinnebusch
year: 2009
doi: 10.1016/j.cell.2009.01.042
source: sonenberg-2009-regulation-translation-initiation.md
category: transcriptomics
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/Regulation-of-Translation-Initiation-in-Eukaryotes.pdf
pdf_filename: Regulation-of-Translation-Initiation-in-Eukaryotes.pdf
source_collection: external
tags: [translation initiation, eIF, scanning, start codon selection, mTOR, ISR, IRES, miRNA, uORF, eIF2, eIF4F]
---

## Summary
This 2009 Cell review by Sonenberg and Hinnebusch provides a comprehensive account of eukaryotic translation initiation—from assembly of the 43S pre-initiation complex (PIC) through 5'UTR scanning to AUG recognition—and describes the global and gene-specific regulatory strategies cells use to control this process. Compared to transcriptional regulation, translational control allows faster changes in protein levels and is critical for nutrient sensing, stress responses, development, and neurological function. The review emphasizes two major global regulatory axes: eIF2α phosphorylation (integrated stress response) and the mTORC1/4E-BP pathway, as well as gene-specific control by uORFs, IRESs, and miRNAs.

## Key Contributions
- **Scanning mechanism and AUG fidelity**: The 43S PIC (40S + Met-tRNAi + eIF1/1A/2/3/5) binds at the 5' cap and scans in an open conformation; eIF1 enforces rejection of non-AUG codons; AUG recognition triggers eIF1 dissociation and irreversible eIF2-GTP hydrolysis, locking in the start codon.
- **eIF4F and mRNA activation**: eIF4E binds m7G cap; eIF4G scaffolds eIF4A helicase; eIF4A unwinds 5'UTR secondary structure; PABP-eIF4G interaction circularizes the mRNA ("closed loop"), enhancing initiation.
- **Integrated stress response (ISR)**: Four eIF2α kinases (HRI, PKR, PERK, GCN2) phosphorylate eIF2α-Ser51 under distinct stress conditions; reduces TC availability; globally inhibits initiation but paradoxically upregulates ATF4/GCN4 via uORF-mediated re-initiation.
- **mTORC1 signaling**: Phosphorylates 4E-BPs (releasing them from eIF4E) and S6K1; integrates nutrient/growth factor signals to set the global rate of cap-dependent translation.
- **DHX29**: Required for scanning through highly structured 5'UTRs; occupies the mRNA entry channel of 40S ribosomes; knockdown causes polysome disassembly.
- **Gene-specific mechanisms**: uORFs, IRESs, and miRNAs provide mRNA-level control overlaid on the global initiation framework.

## Methodology and Architecture
The review synthesizes genetic and biochemical data from yeast and mammalian reconstituted systems, cryo-EM structures, and genetic knockdown experiments:

- **43S PIC assembly**: eIF2-GTP-Met-tRNAi (ternary complex, TC) + eIF1 + eIF1A + eIF3 + eIF5 form on the 40S subunit. eIF3 occupies the solvent backside of 40S and bridges to eIF4G on the mRNA.
- **eIF1 gate-keeper**: In open conformation, eIF1 stabilizes the mRNA channel and blocks premature Pi release from eIF2-GDP-Pi; AUG codon in P-site triggers eIF1 displacement, Pi release, and irreversible commitment to that start codon.
- **eIF2B recycling**: eIF2B (GEF) exchanges GDP for GTP on eIF2; phospho-eIF2α competitively inhibits eIF2B, reducing TC levels when eIF2α is phosphorylated by stress kinases.
- **ISR and uORF logic**: GCN4/ATF4 mRNAs have multiple uORFs; at high TC levels most ribosomes translate inhibitory uORFs and fail to reach the main ORF; at low TC levels (stress), ribosomes scanning past inhibitory uORFs re-acquire TC and reinitiate at the main ORF.

## Results
- Structural studies: eIF1 mutations that allow premature release increase UUG initiation; eIF1A C-terminal extension promotes scanning, N-terminal extension promotes start codon commitment.
- eIF3 cryo-EM: occupies backside of 40S across multiple sites; the j-subunit blocks mRNA binding near the A-site until TC is loaded.
- DHX29 knockdown in human cells causes polysome loss; reconstitution shows it is specifically required for structured-5'UTR mRNAs.
- mTORC1: rapamycin treatment increases 4E-BP binding to eIF4E and reduces protein synthesis; genetic ablation of 4E-BP1/2 partially phenocopies mTOR overactivation.
- miRNA repression: RISC on 3'UTR inhibits early steps of initiation (cap recognition or 60S joining) and promotes deadenylation/mRNA decay.
- IRES: Poliovirus 2A protease cleaves eIF4G; cellular mRNA translation drops; poliovirus IRES continues via direct binding to the intact eIF4G C-terminal portion.

## Related Papers
- [[transcriptomics/moore-2009-premrna-processing-reaches-back]] — upstream nuclear events that produce the mRNA substrate for translation; EJC and pioneer round of translation
- [[transcriptomics/sharp-2009-centrality-of-rna]] — broader context for RNA regulation including miRNA mechanisms that target translation
- [[transcriptomics/cullen-2009-viral-rnas-lessons-enemy]] — IRES elements and ribosomal frameshifting as viral strategies to hijack or modify translation initiation
- [[transcriptomics/houseley-2009-many-pathways-rna-degradation]] — mRNA decay pathways that are coupled to translation (NMD, NSD, NGD)
- [[transcriptomics/cooper-2009-rna-and-disease]] — diseases affecting translation (Fragile X, SMA, DBA) and listed in the trans-acting mutations table
