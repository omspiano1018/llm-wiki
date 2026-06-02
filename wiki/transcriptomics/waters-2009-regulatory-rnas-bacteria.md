---
title: "Regulatory RNAs in Bacteria"
authors: Lauren S. Waters, Gisela Storz
year: 2009
doi: 10.1016/j.cell.2009.01.043
source: waters-2009-regulatory-rnas-bacteria.md
category: transcriptomics
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/Regulatory-RNAs-in-Bacteria_cell.pdf
pdf_filename: Regulatory-RNAs-in-Bacteria_cell.pdf
source_collection: external
tags: [bacterial sRNA, riboswitch, base-pairing, CRISPR, Hfq, CsrA, 6S RNA, gene regulation, RNA regulation]
---

## Summary
This 2009 Cell review by Waters and Storz surveys the known mechanisms and roles of regulatory RNAs in bacteria, organized into four major classes: (1) riboswitches in the 5'UTR of mRNAs; (2) sRNAs that bind and antagonize global regulatory proteins; (3) trans-acting base-pairing sRNAs that modulate translation and mRNA stability; and (4) CRISPR RNAs that protect against foreign DNA. Written just as deep sequencing was beginning to reveal the full scope of these regulators, the review notes that ~80 sRNAs had been verified in E. coli alone (2% of genes) and that hundreds of candidates exist across bacterial genomes.

## Key Contributions
- **Riboswitch diversity and mechanism**: Aptamer + expression platform bipartite structure; ligand binding (SAM, FMN, thiamin, lysine, guanine, etc.) induces conformational change forming/disrupting transcription terminators or translation-inhibitory hairpins. Up to 2% of B. subtilis genes regulated by riboswitches.
- **Protein-binding sRNAs**: CsrB/CsrC titrate CsrA away from its mRNA targets; 6S RNA sequesters σ70-RNA polymerase from some promoters; GlmY protects GlmZ from YhbJ-mediated cleavage in a regulatory cascade.
- **Base-pairing sRNAs and Hfq**: Most base-pairing sRNAs require Hfq chaperone for pairing with target mRNAs (imperfect complementarity); mechanism typically involves blocking ribosome-binding site or coupled degradation by RNase E. Regulate iron homeostasis (RyhB), stress responses, outer membrane composition, virulence.
- **CRISPR RNAs**: Spacers from phage/plasmid genomes are transcribed and processed into crRNAs; provide adaptive immunity; mechanism of DNA targeting was unknown in 2009.
- **Historical context**: Bacterial sRNAs (RNA I, Tn10 antisense, MicF) predated eukaryotic miRNA/siRNA discovery; however, their prevalence and importance were only fully appreciated after 2001–2002 systematic searches.

## Methodology and Architecture
Discovery approaches reviewed: computational searches for conservation + intergenic orphan promoters/terminators; direct cloning of small RNAs; microarray tiling; deep sequencing (Sittka et al., 2008). Mechanisms established through in vitro pairing assays, structural probing, genetics (target identification via overexpression, deletion, compensatory mutations), and reporter fusions.

Key structural/mechanistic frameworks:
- Riboswitch: aptamer recognizes ligand with high affinity and specificity; expression platform converts binding event into conformational change affecting RNA Pol elongation or ribosome loading.
- Hfq: donut-shaped Sm-family hexamer; binds U-rich sequences on sRNAs and A/U-rich sequences on mRNA targets; brings sRNA and mRNA into proximity for pairing; also stabilizes sRNAs from degradation.
- RNase E: C-terminal domain interacts with Hfq; recruited to sRNA-mRNA duplexes for coupled degradation.

## Results
- glmS riboswitch is also a ribozyme: self-cleaves upon glucosamine-6-phosphate binding, providing the only known example of a riboswitch that is also an enzyme.
- Tandem riboswitches integrate multiple signals (e.g., SAM + AdoCbl); the same aptamer domain can mediate different outcomes in different genomic contexts (e.g., cobalamin riboswitch acts by transcription termination in Gram-positives and translation control in Gram-negatives).
- Some sRNAs (RNAIII, 514 nt) also encode small proteins, demonstrating that "noncoding" is not absolute.
- RyhB (iron-responsive sRNA): base-pairs with mRNAs encoding iron-storage proteins, directing their degradation under iron-limiting conditions; conserved in many bacteria.
- CRISPR spacers match known phage sequences, establishing CRISPRs as an acquired adaptive immune memory system.

## Related Papers
- [[transcriptomics/sharp-2009-centrality-of-rna]] — broader perspective on RNA's roles in gene regulation; parallels bacterial sRNA function to eukaryotic miRNA/siRNA mechanisms
- [[transcriptomics/westhof-2009-dynamic-landscapes-rna-architecture]] — structural principles of RNA folding relevant to riboswitch aptamer architecture
- [[transcriptomics/houseley-2009-many-pathways-rna-degradation]] — RNA degradation machinery (including RNase E homologs) that degrades sRNA-mRNA duplex targets
- [[transcriptomics/cullen-2009-viral-rnas-lessons-enemy]] — comparison point: viral RNA regulatory elements use analogous mechanisms (structured RNAs controlling gene expression) in a different biological context
