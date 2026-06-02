---
title: "Ionic-Liquid RNA Storage — Physical State of the RNA and How Hydrolysis Is Suppressed in Aqueous IL Media"
type: overview
category: overviews
synthesizes:
  - pedro-2018-cholinium-based-goods-buffers
  - de-silva-2026-a-biocompatible-and-recyclable
  - alfuhaid-2025-nades-biocompatible-media-thermally
source_collection: external
tags: [ionic-liquid, RNA-storage, hydrolysis, water-activity, choline, RNA-integrity, cold-chain-free, mechanism]
---

## Scope
This overview answers two practical questions about storing RNA in ionic liquid (IL) media:
1. **In what physical state does the RNA exist** during IL storage?
2. **If the medium is aqueous, why doesn't water hydrolyze the RNA?**

All claims are grounded in papers held in this wiki — primarily [[computational/pedro-2018-cholinium-based-goods-buffers]] (recombinant small RNA in cholinium Good's-buffer ILs) and [[computational/de-silva-2026-a-biocompatible-and-recyclable]] (heterogeneous plant total RNA in choline glutamate). The natural deep eutectic solvent (NADES) variant is in [[computational/alfuhaid-2025-nades-biocompatible-media-thermally]].

---

## 1. Physical state of the RNA during storage

The RNA is **dissolved (solvated) in an aqueous IL solution** — not a dry pellet, not frozen.

- de-silva-2026: total plant RNA (150 ± 10 ng/µL) is **dissolved in 20% (w/v) choline glutamate IL solution** and held at room temperature or elevated temperature.
- pedro-2018: recombinant sRNA is dissolved in **20–50% (w/w) GB-IL aqueous solution**.
- The RNA **keeps its native folded (A-form) secondary structure** while dissolved: CD shows the A-form positive Cotton effect near 265 nm, and a melting temperature (Tm) can be measured (de-silva-2026 §3.3). Molecular-dynamics simulations show the RNA sits inside an **"ion atmosphere" / first solvation layer** of choline cations and IL anions (pedro-2018).

### Recovery workflow (de-silva-2026, Fig. 8)
1. **Store**: RNA dissolved in 20% (w/v) choline glutamate IL solution.
2. **Precipitate**: selectively precipitate RNA with ethanol + centrifugation → RNA pellet.
3. **Recycle IL**: regenerate the supernatant IL by rotary evaporation (solvent removal); reuse for the next cycle (≥5 cycles, de-silva-2026).
4. **Recover**: reconstitute the RNA pellet in RNase-free water for downstream analysis.

So the state changes across the workflow: **stored = dissolved in aqueous IL → recovered = ethanol-precipitated pellet → redissolved in water.**

---

## 2. Why aqueous IL media suppress (not eliminate) water-driven hydrolysis

The concern is valid: water-mediated hydrolysis is the **intrinsic** RNA failure mode, and the IL does not make the system anhydrous. It **manages** water rather than removing it.

### The degradation chemistry (why water/structure matters)
RNA's **2′-OH performs an in-line nucleophilic attack on the adjacent 3′-phosphodiester bond**, cleaving the backbone. This happens spontaneously and is **accelerated by alkaline pH, heat, and nucleases** (de-silva-2026, Introduction). The 2′-OH is exactly why RNA is far more labile than DNA.

### Four mechanisms by which a well-chosen IL slows it
1. **Lowered free-water activity / non-hydrolytic environment** — high ion content (20–50%) reduces the free water around the RNA and creates an environment that also **inactivates nucleases** (de-silva-2026, citing choline dihydrogen phosphate work).
2. **Ion atmosphere displaces/reorganizes water and screens charge** — MD shows, within 4 Å of the RNA, ~14 choline cations and 9–12 IL anions in the first solvation layer; the number of cations is similar across ILs but the **anion identity tunes the electrostatic environment** (pedro-2018).
3. **Structural reinforcement (higher Tm)** — a more rigidly folded duplex constrains the 2′-OH / scissile-phosphate geometry, making in-line attack harder. Choline glutamate raises plant-RNA Tm by **+4 °C** (vs 56 °C in water; de-silva-2026); GB-ILs raise sRNA Tm by **up to +14 °C** (pedro-2018).
4. **Nuclease (RNase) inactivation** — the choline cation inactivates ribonucleases, removing the enzymatic hydrolysis route (de-silva-2026).

### ⚠️ The critical caveat: pH and IL choice can *accelerate* hydrolysis
The papers contain their own counter-examples proving water/pH hydrolysis is real:
- **RNA hydrolyzes fastest at pH < 5 (and under alkaline conditions)** (pedro-2018).
- **Unbuffered choline dihydrogen phosphate is strongly acidic (pH < 4)** → it *promotes* hydrolysis and destabilizes the structure (Tm −11.5 °C). It had to be **neutralized to pH 7 with choline hydroxide** to become protective (pedro-2018; de-silva-2026).
- **Choline formate destabilized plant RNA** (Tm drop, collapsed RIN) — the wrong anion makes the same aqueous environment worse (de-silva-2026).

Therefore protection requires an IL that is **near-neutral / self-buffering and structure-reinforcing** (choline glutamate; cholinium Good's-buffer ILs such as [Ch][MES]/[Ch][TES]/[Ch][HEPES]/[Ch][Tricine]).

---

## Key takeaways
- During IL storage the RNA is **dissolved and natively folded inside an aqueous IL solution**, recovered by ethanol precipitation.
- Water-driven hydrolysis is **suppressed, not removed**. The IL approach *manages* water (low free-water activity + structural reinforcement + neutral pH + nuclease inactivation), in contrast to **dry-state methods that remove water entirely** (GenTegra, RNAshell, lyophilization — see de-silva-2026 comparison; [[computational/khan-2025-freeze-drying-mrna-lnps-vaccines]], [[computational/zhen-2026-drying-technologies-messenger-rna]]).
- The **wrong IL or wrong pH (acidic/unbuffered) makes the same aqueous medium accelerate hydrolysis** — IL selection and pH control are decisive.

## Related Papers
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — cholinium Good's-buffer ILs; +14 °C Tm; MD of the RNA first solvation layer; pH neutralization requirement
- [[computational/de-silva-2026-a-biocompatible-and-recyclable]] — 20% (w/v) choline glutamate for plant total RNA; dissolve→precipitate→recycle workflow; 2′-OH degradation rationale
- [[computational/alfuhaid-2025-nades-biocompatible-media-thermally]] — choline-chloride NADES variant; low water activity / H-bond network rationale
- [[computational/kornienko-2024-rna-stability-review-structural]] — general review of structural/environmental determinants of RNA stability (2′-OH hydrolysis, pH, oxidation)
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — broader IL/DES stabilization perspective for nucleic-acid biopharmaceuticals
