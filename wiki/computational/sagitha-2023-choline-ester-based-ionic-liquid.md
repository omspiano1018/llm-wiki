---
title: "Choline ester based ionic liquid: A multi-functional system to enhance nucleic acid stability, drug solubilization and cell penetration"
authors: P. Sagitha, Hemavathi Dhandapani, Prakriti Tayalia
year: 2023
doi: 10.1016/j.ijbiomac.2023.124059
source: sagitha-2023-choline-ester-based-ionic-liquid.md
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/sagitha-2023-choline-ester-based-ionic-liquid.pdf
pdf_filename: sagitha-2023-choline-ester-based-ionic-liquid.pdf
source_collection: external
tags: [ionic-liquid, choline, nucleic-acid, DNA, zeta-potential, citric-acid, nuclease-protection, doxorubicin, cell-penetration, biocompatible, experimental]
---

## Summary
A hands-on experimental paper (IIT Bombay, 2023): a biocompatible **propionyl-choline-chloride IL ([Ch] IL)** that does three jobs at once — binds/stabilizes DNA, protects it from nucleases (long-term storage), and improves the aqueous solubility + cellular uptake of a drug (doxorubicin). The key practical lesson for delivery work: a positively charged choline IL complexes DNA well in vitro, **but the complex flips to negative zeta potential and falls apart at physiological pH** — fixed here by adding **citric acid** to keep the complex positive and stable. This is the concrete experiment behind the "citric acid / zeta potential" example in [[cell-biology/lee-2026-ionic-liquid-enabled-drug-delivery-systems]].

## Key Contributions
- A single **multi-functional choline IL**: nucleic-acid binding/stabilization **+** drug solubilization/uptake
- Diagnoses and fixes the **physiological-pH dissociation** of IL–DNA complexes via citric acid (zeta potential ↑ → stable complex)
- DNA is **recoverable from the complex with intact purity/integrity** (reversible — works as a storage matrix)
- Confirms biocompatibility (MTT proliferation + hemolysis)

## Methodology and Architecture
- **Synthesis**: [Ch] IL = choline chloride + propionyl chloride (1:1.5), 70 °C reflux 24 h in DCM, cold-ether precipitation; amino-acid variants (Pro/Gly/Ala) by Ag₂O salt metathesis + lyophilization
- **DNA work**: agarose electrophoresis, EtBr dye-displacement, UV absorbance; pH-dependent complex stability; DNase protection assay; plasmid DNA via CsCl
- **Drug/cell work**: doxorubicin solubilization + concentration-dependent uptake; MCF-7 cells; FT-IR and Malvern zeta sizing

## Results
- **[Ch] IL**: positive zeta potential, effective DNA complexation — **but destabilizes at physiological pH** (zeta → negative)
- **[CA-Ch] IL** (with citric acid): higher zeta potential → **stable IL–DNA complex at physiological pH**
- **Nuclease protection** + long-term DNA stability in the complexed state
- **Reversible**: DNA retrieved with preserved purity/integrity
- **Drug uptake**: [Ch] IL raises doxorubicin solubility and **enhances cellular uptake, concentration-dependently**
- **Biocompatible**: both ILs pass proliferation + hemolysis tests

## Why this matters for an RNA-delivery program
- The **zeta-potential-at-physiological-pH trap** is directly transferable: a cationic IL that condenses your nucleic acid in the tube can dissociate in physiological buffer/serum. Watch zeta potential under physiological conditions, not just in water.
- **Citric acid (or another modifier) as a stabilizer** of the cationic complex is a cheap, biocompatible lever.
- **Caveat**: demonstrated on **plasmid DNA**, and the cargo delivered into cells here is a small molecule (doxorubicin), not RNA — so treat it as mechanism/insight, not a validated RNA-transfection system.

## Related Papers
- [[computational/egorova-2021-ionic-liquids-prospects-for-nucleic]] — review that frames this class of cationic-choline-IL nucleic-acid systems
- [[computational/mirhadi-2024-utilizing-ionic-liquids-as-eco]] — delivery review consistent with this multi-functional-IL approach
- [[computational/pedro-2018-cholinium-based-goods-buffers]] — choline-IL nucleic-acid stabilization, focused on RNA (Tm/storage) rather than complexation
- [[computational/verissimo-2026-ionic-liquids-deep-eutectic]] — biopharmaceutical IL/DES review (siRNA/mRNA/ASO)
- [[cell-biology/lee-2026-ionic-liquid-enabled-drug-delivery-systems]] — cites this as the citric-acid/zeta-potential nucleic-acid example
