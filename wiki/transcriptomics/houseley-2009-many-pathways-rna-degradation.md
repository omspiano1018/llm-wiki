---
title: "The Many Pathways of RNA Degradation"
authors: Jonathan Houseley, David Tollervey
year: 2009
doi: 10.1016/j.cell.2009.01.019
source: houseley-2009-many-pathways-rna-degradation.md
category: transcriptomics
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/The-Many-Pathways-of-RNA-Degradation_cell.pdf
pdf_filename: The-Many-Pathways-of-RNA-Degradation_cell.pdf
source_collection: external
tags: [RNA degradation, exosome, TRAMP, Xrn1, decapping, deadenylation, NMD, RNA surveillance, RNA quality control, miRNA, siRNA, Ccr4-NOT]
---

## Summary
This 2009 Cell review by Houseley and Tollervey systematically covers all major pathways through which RNA is degraded in cells, from bacteria to eukaryotes. The central theme is that RNA degradation is both universal and tightly controlled: the same RNases that process stable RNAs to their mature forms also completely degrade aberrant or unwanted RNAs, with cofactors (helicases, polymerases, chaperones) providing the substrate specificity that distinguishes these fates. Particularly important contributions are the description of the nuclear TRAMP complex as the major RNA quality control scaffold, the integration of small RNA-directed degradation with the bulk decay machinery, and a comprehensive table mapping yeast RNA degradation factors to their human homologs.

## Key Contributions
- **Three classes of RNases**: Endonucleases, 5' exonucleases (Rat1/Xrn1 family), and 3' exonucleases (exosome); present in all life; recently shown to include 5' exonucleases in bacteria.
- **TRAMP complex**: Yeast nuclear RNA surveillance scaffold (Trf4/5 poly(A) polymerase + Air1/2 zinc-knuckle + Mtr4 helicase); adds short poly(A) tags to defective nuclear RNAs as a "landing pad" for exosome degradation; conceptually analogous to polyubiquitylation.
- **Eukaryotic mRNA decay pathways**: Deadenylation (Ccr4-NOT) → decapping (Dcp1/Dcp2) → 5'→3' Xrn1 degradation; OR deadenylation → 3'→5' exosome + Ski complex; special pathways for aberrant mRNAs (NMD, NSD, NGD).
- **Small RNA-directed degradation**: miRNA-RISC promotes deadenylation and mRNA destabilization; siRNA-RISC cleaves perfectly complementary targets; piRNAs suppress transposons.
- **Evolutionary model**: Ancestral RNA degradation was stimulated by 3' heteropolymeric tail addition (by PNPase/archaeal exosome); dedicated poly(A) polymerases arose later; nuclear polyadenylation-for-degradation is evolutionarily prior to cytoplasmic polyadenylation-for-stability.
- **Human homologs table** (Table 1): Complete mapping of ~30 yeast degradation factors to their human counterparts with percent identity, covering exosome, TRAMP, Ccr4-NOT, Lsm, Ski, and decapping complexes.

## Methodology and Architecture
Review covers biochemistry, genetics, and structural studies of RNA degradation:

- **Exosome**: 9-subunit barrel core (Csl4, Rrp4, Rrp40, Rrp41, Rrp42, Rrp43, Rrp45, Rrp46, Mtr3); single catalytic subunit Rrp44/Dis3 (3' hydrolytic exonuclease + endonuclease); nuclear Rrp6 adds additional hydrolytic activity.
- **Helicase cofactors**: Mtr4 (nuclear, TRAMP) and Ski2 (cytoplasmic, Ski complex) assist exosome by unwinding substrates; RhlB assists bacterial PNPase/degradosome.
- **Polyadenylation for degradation**: TRAMP-added poly(A) extends past 3' hairpins to provide landing pad; conceptually parallel to poly(U) polymerase in human histone mRNA decay (Lsm1-7 recruitment).
- **mRNA decay pathway logic**: Most mRNAs first deadenylated by Ccr4-NOT; then either decapped (→ Xrn1) or 3'→5' exosome-degraded; P-bodies are sites of mRNA storage/decapping.
- **Quality control pathways**: NMD (premature stop codon + downstream EJC → Upf1/2/3 activation → decapping/degradation); NSD (no stop codon → ribosome stalls at 3' end → Ski complex + Dom34/Hbs1 → exosome); NGD (no-go decay, stalled ribosome → endonucleolytic cleavage).

## Results
- 5' exonucleases were recently discovered in bacteria (de la Sierra-Gallay et al., 2008; Mathy et al., 2007), completing the parallel between bacterial and eukaryotic degradation enzyme classes.
- Human TRAMP component homologs exist (POLS/PAPD5 for poly(A) polymerase; SKIV2L2 for Mtr4 helicase; ZCCHC3 for Air) with 36–52% identity; functional characterization pending.
- Poly(U) polymerases in many eukaryotes (including humans) add poly(U) tails that stimulate Lsm1-7-mediated decay; this pathway may be as widespread as polyadenylation-mediated decay.
- The Ski complex (Ski2-Ski3-Ski8) in yeast provides the cytoplasmic exosome cofactor; human SUPV3L1 is a Ski2 homolog; loss of Ski components impairs antiviral defense (originally identified as "superkiller" for susceptibility to viral dsRNA).
- piRNA pathway uses Piwi/Argonaute-family proteins and ping-pong amplification to enforce transposon silencing in animal germlines; co-opts the core Argonaute endonuclease activity of RISC.

## Related Papers
- [[transcriptomics/moore-2009-premrna-processing-reaches-back]] — NMD is triggered by the EJC deposited during splicing; processing and degradation are coupled
- [[transcriptomics/cooper-2009-rna-and-disease]] — NMD and RNA decay pathway mutations cause disease (UPF3B in X-linked intellectual disability, DKC1 in dyskeratosis congenita)
- [[transcriptomics/waters-2009-regulatory-rnas-bacteria]] — bacterial RNA degradation (RNase E, PNPase, degradosome) reviewed as evolutionary context for eukaryotic pathways
- [[transcriptomics/westhof-2009-dynamic-landscapes-rna-architecture]] — RNA secondary structures (stable hairpins) create barriers to exonuclease degradation that require helicase cofactors
- [[transcriptomics/sharp-2009-centrality-of-rna]] — miRNA/siRNA regulation is mediated in part through RISC-directed mRNA degradation reviewed here
