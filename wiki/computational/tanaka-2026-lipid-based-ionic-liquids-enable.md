---
title: "Lipid-based ionic liquids enable efficient messenger RNA intracellular delivery"
authors: Keisuke Tanaka, Yoshirou Kawaguchi, Rie Wakabayashi, Noriho Kamiya, Masahiro Goto
year: 2026
doi: 10.1093/chemle/upag025
source: tanaka-2026-lipid-based-ionic-liquids-enable.md
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Lipid-based ionic liquids enable efficient messenger RNA intracellular delivery.pdf
pdf_filename: Lipid-based ionic liquids enable efficient messenger RNA intracellular delivery.pdf
source_collection: external
tags: [ionic-liquid, lipid-based-ionic-liquid, mRNA-delivery, transfection, cationic-phospholipid, LBIL, RNA-DDS]
---

## Summary
This Letter reports **lipid-based ionic liquids (LBILs)** in which *the lipid itself is the ionic liquid* — a cationic ethylated phosphocholine paired with a fatty-acid (linoleate) anion — used to complex and deliver **messenger RNA** into cells. Three cationic phospholipids of increasing alkyl-chain length (DMPC C14, DPPC C16, DSPC C18) were ethylated and paired with linoleate to give **[EDMPC][Lin]**, **[EDPPC][Lin]**, **[EDSPC][Lin]**. The hydrophobic tail controls complex size, surface charge, and mRNA binding. **[EDMPC][Lin]** (myristoyl) forms the smallest, most positively charged, most stable mRNA complexes and gives the **highest NanoLuc-mRNA transfection in HeLa cells**, establishing LBILs as a tunable single-molecule platform for intracellular mRNA delivery.

This is the wiki's clearest example of *"converting a lipid into an ionic liquid"* for RNA DDS — distinct from [[computational/yu-2026-ionic-liquids-as-alternative]], where an IL serves as an additive/stabilizer in a conventional LNP rather than being the cationic lipid itself.

## Key Contributions
- **First LBIL-mediated mRNA delivery** (prior LBIL work from the same group, Toyofuku et al. 2023, delivered only antisense oligonucleotides).
- Systematically varies the **cation (lipid tail) design** — the variable previously held fixed — across C14/C16/C18 phosphocholines with a common linoleate anion.
- Demonstrates a **non-monotonic structure–activity relationship**: tail length governs size, zeta potential, mRNA binding, and transfection, but the best performer is the *shortest* tail (myristoyl), implicating lipid packing/headgroup/hydration.
- Identifies **[EDMPC][Lin]** as the lead: +36.6 mV, single-population particles, full mRNA retention on gel, highest gene expression.

## Methodology and Architecture
- **Synthesis (2 steps)**: (1) ethylate phospholipid with ethyl triflate (1:1, 45 °C, 12 h, N₂) → quaternized cationic lipid, converted to chloride form; (2) anion exchange with linoleic acid (free fatty acid, equimolar, chloroform, 45 °C overnight) → IL-type lipid; lyophilize (volatile HCl byproduct escapes, driving the exchange and removing Cl⁻); **¹H-NMR in DMSO-d₆ (400 MHz)** confirmed (SI Fig. S1). Tanaka's text writes only "linoleate" and cites ref. 17; the free-acid route is per the founding method [[computational/uddin-2020-lipid-based-biocompatible-ionic-liquids]].
- **mRNA**: NanoLuc mRNA made in-house by **IVT** (Takara IVTpro™ T7 kit, **modified NTPs**), LiCl-precipitated and purified (SI).
- **Complexation**: LBIL (ethanol) + NanoLuc mRNA (water) at **N/P = 10:1**, RT 5 min.
- **Characterization**: DLS (size, incl. LBILs alone — SI Fig. S2: EDSPC–Lin aggregates while EDMPC/EDPPC–Lin stay submicron), zeta potential (n = 5), agarose gel electrophoresis (binding/retardation).
- **Transfection**: HeLa cells, 500 ng mRNA/well, 24 h, NanoLuc luminescence (n = 3, Tukey's test), with **Lipofectamine** as benchmark.

## Results
| LBIL | Cation tail | Zeta potential | mRNA binding (gel) | Transfection |
|------|-------------|----------------|--------------------|--------------|
| **[EDMPC][Lin]** | C14 myristoyl | **+36.6 mV** | retained in well | **highest** |
| [EDSPC][Lin] | C18 stearoyl | +23.2 mV | retained in well | high (> free mRNA) |
| [EDPPC][Lin] | C16 palmitoyl | **−36.6 mV** | partial migration (free mRNA) | ≈ free mRNA (no benefit) |

- Particle size: EDMPC-Lin < EDPPC-Lin < EDSPC-Lin (longer tails aggregate in water/ethanol).
- Positive surface charge correlates with charge-neutralized, stable complexes and higher delivery; the C16 (EDPPC) anomaly (negative zeta, incomplete complexation) breaks the monotonic trend.
- **In vitro only**; no in vivo data or cytotoxicity reported; single reporter and single anion (linoleate).

## Related Papers
- [[computational/uddin-2020-lipid-based-biocompatible-ionic-liquids]] — **founding LBIL synthesis paper** from the same group; introduces the EDMPC + C18-fatty-acid chemistry (incl. linoleate) and gives the full quantitative synthesis/purification this Letter only references. The direct ancestor of this work.
- [[computational/yu-2026-ionic-liquids-as-alternative]] — also IL-for-mRNA-delivery, but the IL is an LNP stabilizer (PEG replacement), not the cationic lipid; contrast in molecular role.
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — review framing surface-active ILs / API-ILs as combined protection + delivery agents for nucleic acids; LBILs are an instance of this concept.
- [[cell-biology/mitragotri-2024-choline-geranate-cage-multifaceted]] — CAGE IL for transdermal small-molecule/siRNA delivery; different IL chemistry and route.
- [[cell-biology/zakrewsky-2014-ionic-liquids-as-a-class]] — original CAGE / IL-panel discovery (includes fatty-acid anion ILs such as choline oleate/hexanoate).
- [[transcriptomics/bonetta-2009-rna-based-therapeutics-delivery]] — earlier survey identifying intracellular delivery as the central bottleneck for RNA therapeutics (the problem LBILs address).
- [[overviews/ionic-liquid-rna-storage-state-and-hydrolysis]] — companion theme: how RNA behaves in ionic-liquid environments (storage/stabilization vs. delivery).
