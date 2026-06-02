---
title: "Transcriptional Scaffolds for Heterochromatin Assembly"
authors: Hugh P. Cam, Ee Sin Chen, Shiv I.S. Grewal
year: 2009
doi: 10.1016/j.cell.2009.02.004
source: grewal-2009-transcriptional-scaffolds-heterochromatin.md
category: epigenomics
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/Transcriptional-Scaffolds-for-Heterochromatin-Asse.pdf
pdf_filename: Transcriptional-Scaffolds-for-Heterochromatin-Asse.pdf
source_collection: external
tags: [heterochromatin, RNAi, siRNA, HP1, H3K9 methylation, fission yeast, RITS, RDRC, Xist, imprinting, ncRNA, epigenomics, transcriptional silencing]
---

## Summary
This 2009 Cell essay by Cam, Chen, and Grewal presents evidence from fission yeast, plants, and mammals that RNA Pol II transcription and its noncoding products are not silenced at heterochromatic loci but are actively required to nucleate and propagate heterochromatin. The key concept is "transcriptional hijacking": Pol II transcription of centromeric repeats is co-opted to recruit heterochromatin assembly factors (via RNAi and chromatin-modifying complexes) rather than to produce functional gene products. In mammals, long noncoding RNAs (Xist, Air, Kcnq1ot1) serve as structural scaffolds that recruit Polycomb and histone methyltransferase complexes to silence specific chromosomal domains.

## Key Contributions
- **Transcriptional hijacking model**: What distinguishes heterochromatin is not the absence of transcription but the redirection of Pol II transcription toward heterochromatin assembly rather than gene expression.
- **RNAi-mediated centromeric heterochromatin (S. pombe)**: Centromeric repeat transcripts are processed into siRNAs by RITS + RDRC + Dcr1; siRNAs guide ClrC (Clr4 H3K9 methyltransferase) to the locus; H3K9me recruits HP1 (Swi6, Chp1) → spreading via positive feedback loop (Clr4 chromodomain binds H3K9me).
- **Cell cycle regulation**: S phase heterochromatin is more permissive; elevated Pol II activity at centromeric repeats recruits ClrC and RITS; H3K36me3 by Set2 (coupled to Pol II elongation) recruits HDAC Clr6 to ensure coupling of transcription to silencing.
- **Plant RdDM**: RNA Pol IV generates siRNA precursors → DCL3 → 24 nt siRNAs → AGO4 → RNA Pol V → DRM2 DNA methyltransferase → de novo cytosine methylation at transposons.
- **Mammalian XCI and imprinting by lncRNAs**: Xist recruits PRC2 (via direct binding to short RNA repeats within Xist) for H3K27me3 spreading across the inactive X; Air binds G9a methyltransferase for imprinted silencing of Slc22a3 in placenta.

## Methodology and Architecture
Essay synthesizes genetic and molecular biology data from multiple systems:

- **S. pombe genetics**: RNAi component knockouts (Dcr1, Ago1, Rdp1) disrupt centromeric silencing and H3K9me; Clr4 chromodomain mutations disrupt H3K9me spreading and RITS localization.
- **ChIP and siRNA cloning**: Demonstrates H3K9me, HP1, ClrC, and RITS co-localizations at centromeric repeats; siRNA cloning confirms centromeric origin.
- **Time-resolved ChIP during cell cycle**: Shows S phase increase in Pol II at centromeric repeats correlates with peak ClrC and RITS recruitment; G2 shows HP1 spreading and silencing complex consolidation.
- **Mammalian lncRNA studies**: Deletion constructs and allele-specific ChIP; Xist RNA immunoprecipitation with EZH2 (PRC2 subunit); proximity ligation and immunofluorescence for RNA-chromatin contacts.

Key protein complexes:
- **RITS**: Ago1 (Argonaute, loaded with siRNAs) + Chp1 (HP1 family, binds H3K9me) + Tas3 (scaffold); bridges siRNA-loaded Ago1 to chromatin via Chp1-H3K9me.
- **RDRC**: Rdp1 (RNA-dependent RNA polymerase) + Hrr1 + Cid12; amplifies siRNA production; associates with splicing factors (via Cid12) for co-processing of repeat transcripts.
- **ClrC**: Clr4 (SET domain H3K9 methyltransferase) + Rik1 (WD-β-propeller, binds nascent transcripts/RITS) + Cul4 + Dos1/2; recruited by RITS to methylate H3K9 at target loci.

## Results
- Mutations in Pol II or associated factors (Djupedal et al., 2005) severely reduce siRNA production from centromeric repeats and disrupt H3K9me, demonstrating Pol II transcription is required for centromeric RNAi.
- Clr4 chromodomain mutation: abrogates Clr4 association with H3K9me; disrupts RITS chromatin binding and H3K9me spreading (Zhang et al., 2008), confirming positive feedback.
- Rik1 as the bridge: interacts with nascent transcript (via putative RNA-binding domain) and with RITS complex; required for ClrC chromatin targeting and H3K9me (Zhang et al., 2008).
- Xist-PRC2 interaction (Zhao et al., 2008): short RepA RNA repeats within Xist directly bind EZH2; deletion of RepA prevents PRC2 recruitment and blocks XCI spreading.
- Air ncRNA (Nagano et al., 2008): loss of Air ncRNA specifically fails to silence Slc22a3 in placenta; Air RNA co-immunoprecipitates with G9a at the Slc22a3 promoter.

## Related Papers
- [[transcriptomics/sharp-2009-centrality-of-rna]] — broad perspective on RNA regulation including siRNA-directed chromatin silencing described here; RNA as central to both cytoplasmic and nuclear regulation
- [[transcriptomics/waters-2009-regulatory-rnas-bacteria]] — evolutionary context: bacterial CRISPR RNAs and sRNAs use base-pairing to regulate DNA and RNA; parallels to siRNA-based heterochromatin
- [[transcriptomics/carthew-2009-origins-mechanisms-mirnas-sirnas]] — siRNA and piRNA biogenesis mechanisms that feed into the heterochromatin assembly pathway described here
- [[transcriptomics/ponting-2009-evolution-functions-long-noncoding]] — lncRNAs (Xist, Air, Kcnq1ot1) reviewed in detail in Ponting et al.; directly relevant to mammalian heterochromatin section
