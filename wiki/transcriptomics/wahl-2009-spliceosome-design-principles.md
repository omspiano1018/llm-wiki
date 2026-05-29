---
title: "The Spliceosome: Design Principles of a Dynamic RNP Machine"
authors: Markus C. Wahl, Cindy L. Will, Reinhard Lührmann
year: 2009
doi: 10.1016/j.cell.2009.02.009
source: wahl-2009-spliceosome-design-principles.md
category: transcriptomics
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/The-Spliceosome--Design-Principles-of-a-Dynamic-RN.pdf
pdf_filename: The-Spliceosome--Design-Principles-of-a-Dynamic-RN.pdf
source_collection: external
tags: [spliceosome, pre-mRNA splicing, snRNP, snRNA, alternative splicing, DExH helicase, RNP, Sm proteins, U6 snRNA, catalytic RNA, group II intron]
---

## Summary
This landmark 2009 Cell review by Wahl, Will, and Lührmann describes the spliceosome as a fundamentally different RNP machine from the ribosome: while the ribosome is compositionally stable with preformed active sites, the spliceosome is assembled de novo on each pre-mRNA substrate, undergoes ~8 DExH/D helicase-driven remodeling events, and creates its catalytic center only transiently during the reaction cycle. This dynamic design provides both the accuracy needed for precise splice-site selection and the flexibility required for alternative splicing—two goals that are in tension and are reconciled through kinetic proofreading at multiple ATP-dependent steps.

## Key Contributions
- **Dynamic versus stable RNP machines**: The ribosome uses preformed, stable active sites; the spliceosome builds its active site from scratch at every cycle via extensive RNA-RNA and RNA-protein remodeling.
- **Five snRNPs and stepwise assembly**: U1 (5' splice site recognition), U2 (branch point recognition), and tri-snRNP U4/U6.U5 (joins as a pre-formed ~1 MDa unit) assemble into a >5 MDa spliceosome through defined intermediates (E, A, B, Bact, B*, C complexes).
- **Catalytic RNA core**: U6 snRNA (ACAGAGA box, ISL) forms the catalytic center; structurally and mechanistically analogous to group II self-splicing introns, supporting the evolutionary hypothesis that the spliceosome evolved from a group II intron captured from an ancient bacterial invasion.
- **DExH/D helicase-driven remodeling**: Eight conserved helicases (Prp28, Brr2, Prp2, Prp16, Prp22, Prp43, Prp5, Prp11) each catalyze a specific, ordered remodeling event; helicase action provides kinetic proofreading.
- **RNP continuum**: The review places the spliceosome within the broader context of RNP machines that span from true ribozymes (group II introns, where RNA catalyzes and proteins only support) to protein-enzyme RNPs (snoRNPs, where RNA is only a guide), with the spliceosome near the middle.

## Methodology and Architecture
Review integrates biochemical reconstitution, genetic analysis (yeast), cryo-EM, X-ray crystallography of individual snRNP components, and comparative analysis with group II introns:

- **snRNP biogenesis**: Pre-snRNAs exported to cytoplasm; Sm core assembled by SMN complex (PRMT5 methylation of Sm proteins required for recognition); re-imported to nucleus; snRNA 3' processing; snRNA-specific proteins added in Cajal bodies.
- **Assembly transitions**: E complex (no ATP required) → A complex (Prp5/11, ATP) → B complex (Prp28, Brr2, ATP) → Bact (fully remodeled; U4 ejected) → B* (Prp2, ATP; catalytic activation) → C complex (first transesterification) → post-splicing (Prp16, Prp22, Prp43, ATP; product release and disassembly).
- **Proofreading logic**: At each helicase step, correct RNA-RNA contacts slow helicase action (giving time for productive chemistry); mismatched contacts allow faster helicase action that aborts the reaction before catalysis.
- **Two-step transesterification mechanism**: Both steps use the same two-metal-ion mechanism; first step: branch point 2'-OH attacks 5' splice site, producing free 5' exon and lariat-3' exon intermediate; second step: 3'-OH of 5' exon attacks 3' splice site, joining exons and releasing lariat intron.

## Results
- Structural studies on U1 snRNP (~240 kDa) at near-atomic resolution revealed how U1 snRNA loop I base-pairs with the 5' splice site and how U1-specific proteins stabilize this interaction.
- U4/U6 di-snRNP and U4/U6.U5 tri-snRNP cryo-EM maps established the architecture of the pre-activation spliceosome building block.
- Brr2 helicase (within U5 snRNP) unwinds the U4/U6 duplex during spliceosome activation; its activity must be carefully regulated (Prp8 is a key regulator) to prevent premature unwinding.
- Group II intron/spliceosome parallel: both use a 2'-OH nucleophile at a conserved adenosine, form lariat intermediates, use a catalytic RNA with an ACAGAGA-like sequence, and require two Mg2+ ions—strong evidence for a common evolutionary origin.
- >150 proteins associate with the spliceosome transiently; the yeast two-hybrid and mass spectrometry-defined interaction network revealed a complex wiring diagram.

## Related Papers
- [[transcriptomics/moore-2009-premrna-processing-reaches-back]] — spliceosome deposits the EJC during splicing; coupling of splicing to transcription via Pol II CTD
- [[transcriptomics/cooper-2009-rna-and-disease]] — mutations in spliceosome components (PRPF31, PRPF8) cause retinitis pigmentosa; splicing defects in DM1/SMA
- [[transcriptomics/sharp-2009-centrality-of-rna]] — Sharp's essay discusses alternative splicing scope enabled by the spliceosome; over 90% of human genes alternatively spliced
- [[transcriptomics/westhof-2009-dynamic-landscapes-rna-architecture]] — RNA folding principles relevant to U snRNA structure and spliceosome assembly; group II intron structural parallel
- [[transcriptomics/houseley-2009-many-pathways-rna-degradation]] — spliceosome-dependent EJC deposition triggers NMD surveillance in the degradation pathway
