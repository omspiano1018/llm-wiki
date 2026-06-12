---
title: "One-component ionizable amphiphilic Janus dendrimers as a delivery platform for efficient mRNA vaccine development"
authors: Nathan A. Ona, Dapeng Zhang, Lisa C. Lindesmith, et al.; Virgil Percec, Ralph S. Baric, Yongsheng Li, Drew Weissman, Elena N. Atochina-Vasserman
year: 2026
doi: 10.1126/sciadv.adv1554
source: ona-2026-one-component-ionizable-amphiphilic-janus.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/ona-2026-one-component-ionizable-amphiphilic-janus.pdf
pdf_filename: ona-2026-one-component-ionizable-amphiphilic-janus.pdf
source_collection: external
tags: [IAJD, Janus-dendrimer, dendrimersome, one-component, mRNA-vaccine, ionizable, RNA-delivery, spleen-targeting, lymph-node, norovirus, thermostability, PEG-free, LNP-alternative]
---

## Summary
Ona et al. (2026, *Science Advances*, Weissman group) replace the standard **four-component lipid nanoparticle** (ionizable lipid + cholesterol + phospholipid + PEG-lipid) with a **one-component ionizable amphiphilic Janus dendrimer (IAJD)** — a single sequence-defined amphiphile that **self-assembles with mRNA in one mixing step** into onion-like dendrimersome nanoparticles. The lead **IAJD97** (selected from >300 candidates) delivers mRNA selectively to the **spleen and lymph nodes** rather than the liver, is **stable at +4 °C for ≥26 weeks** (mRNA integrity DV200 ≈ 93–95% after 7 months vs **28%** for an SM102 LNP), and is non-toxic up to 30 µg. As a **norovirus mRNA vaccine**, it elicits neutralizing antibodies (durable to ≥day 150), polyfunctional CD4/CD8 T cells, and TFH/germinal-center B cells **equivalent to the clinical four-component SM102 LNP** — while being PEG-free and cholesterol-free.

This is the wiki's example of the **"one-component / single-molecule carrier"** strategy for mRNA, sharing that design philosophy with [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] (the lipid itself is an ionic liquid) but using **Janus-dendrimer chemistry** instead. Its standout angle vs. the rest of the delivery cluster is **lymphoid-organ targeting + refrigerator-stable thermostability**.

## Key Contributions
- **One-component IAJD platform**: a self-assembling Janus dendrimer that needs no cholesterol, helper phospholipid, or PEG-lipid — simpler synthesis, better scalability, no anti-PEG-antibody liability.
- **Spleen/lymph-node tropism**: IAJD97 (two nitrogens + hydroxyethyl amino head) delivers mRNA to lymphoid organs (spleen 590× heart, 18× lung, 9× liver) — ideal for vaccines, unlike the liver-tropic conventional LNPs.
- **Refrigerator stability / cold-chain potential**: stable at +4 °C ≥26 weeks; encapsulated mRNA DV200 ≈ 93–95% after 7 months vs 28% in an SM102 LNP under identical conditions.
- **Vaccine efficacy on par with SM102 LNP**: norovirus VP1 mRNA-IAJD97 matches the clinical benchmark for neutralizing-antibody titers, T-cell, and TFH/GC B-cell responses, with durability to ≥150 days.

## Methodology and Architecture
- **Carrier**: ionizable amphiphilic Janus dendrimer (sequence-defined single molecule, ionizable amino hydrophilic head + dendritic hydrophobic tails); **coassembles with nucleoside-modified mRNA by one-step mixing** → multilamellar "dendrimersome" (onion-like by cryo-TEM). IAJD97 chosen from screening >300 IAJDs / a 31-member "simplified single–single" library.
- **Formulation**: acetate (pH ~4.81) or PBS-diluted (pH ~6.02); 5–10 µg mRNA/mouse (toxicology to 30 µg); characterized by size/PDI, encapsulation efficiency, **pKa**, zeta potential.
- **Readouts**: IVIS bioluminescence (Luc mRNA) for biodistribution/kinetics; Bioanalyzer **DV200** for RNA integrity; IV and i.m. immunization (days 0/28); neutralizing-Ab surrogate (HBGA/VLP blockade, ID50); CD4/CD8 intracellular-cytokine flow cytometry; TFH/GC B-cell enumeration; H&E histopathology + serum ALT/AST.

## Results
| Aspect | IAJD97 (one-component) | Four-component LNP (SM102) |
|--------|------------------------|----------------------------|
| Components | 1 (Janus dendrimer) | 4 (ionizable lipid, cholesterol, phospholipid, PEG-lipid) |
| Biodistribution | Spleen / lymph nodes | Liver-tropic |
| mRNA integrity, 7 mo @ 4 °C | DV200 ≈ 93–95% | DV200 ≈ 28% |
| Vaccine nAb / T-cell | Comparable | Benchmark |
| PEG / cholesterol | None | Required |

- **Kinetics**: spleen luciferase detectable to 96 h.
- **Toxicity**: no inflammation at 10–30 µg; only mild, reversible splenic PALS lymphocyte depletion at 30 µg; no ALT/AST change.
- **Immunity**: minimal effective dose <1 µg; durable nAb to day 150 (ID50 ~3000 at 5 µg i.m.); Th1-biased polyfunctional CD4/CD8 T cells (IFN-γ, IL-2, TNF-α) and robust TFH + GC B cells from a single dose.

## Limitations
- Mouse-only, single pathogen (norovirus) proof of concept; mainly IV dosing; effective dose (5–10 µg) higher than typical mouse LNP (1–3 µg); spleen-targeting mechanism (protein corona) hypothesized not proven; 40-week stability based on n=1.

## Related Papers
- [[computational/tanaka-2026-lipid-based-ionic-liquids-enable]] — the other "one-component / single-molecule" simplification of the 4-component LNP (lipid-based ionic liquid vs Janus dendrimer).
- [[computational/borrajo-2024-ionizable-nanoemulsions-for-rna-delivery]] — also re-engineers LNP architecture (soft nanoemulsion) while keeping an ionizable lipid; contrast: tissue diffusivity (CNS) vs lymphoid-organ targeting (vaccine).
- [[computational/yu-2026-ionic-liquids-as-alternative]] — PEG-replacement in mRNA-LNPs; both papers target the anti-PEG / structural-lipid limitations of four-component LNPs.
- [[computational/zhang-2026-chemical-engineering-mrna-lnp]] — engineering mRNA-LNP stability; IAJD's 4 °C/26-week shelf life is a delivery-side answer to the same thermostability problem.
- [[computational/oude-blenke-2022-storage-inuse-stability-mrna]] — mRNA-LNP storage/degradation chemistry; frames the DV200 stability comparison vs SM102.
- [[computational/alfuhaid-2025-nades-biocompatible-media-thermally]] — cold-chain-free RNA stabilization (NADES); complementary route to refrigerator/ambient-stable mRNA.
- [[transcriptomics/bonetta-2009-rna-based-therapeutics-delivery]] — early framing of delivery as the central RNA-therapeutics bottleneck.
</content>
