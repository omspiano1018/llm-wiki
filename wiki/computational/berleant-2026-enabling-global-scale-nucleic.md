---
title: "Enabling Global-Scale Nucleic Acid Repositories Through Versatile, Scalable Biochemical Selection from Room-Temperature Archives"
authors: Joseph D. Berleant, James L. Banal, Dhriti K. Rao, Mark Bathe
year: 2026
doi: 10.1038/s41467-026-69402-3
source: berleant-2026-enabling-global-scale-nucleic.md
category: computational
pdf_path: C:/Users/painteroh/Desktop/llm-wiki/papers/Enabling global-scale nucleic acid repositories through versatile, scalable biochemical selection from room-temperature archives.pdf
pdf_filename: Enabling global-scale nucleic acid repositories through versatile, scalable biochemical selection from room-temperature archives.pdf
source_collection: external
tags: [nucleic acid repository, room temperature storage, DNA barcode, silica encapsulation, biobank, SARS-CoV-2, database query, scalable retrieval, MIT]
---

## Summary
This 2026 Nature Communications paper from Berleant, Banal, Rao, and Bathe (MIT/Broad Institute) introduces a scalable room-temperature nucleic acid biosample database system that goes beyond prior work by enabling SQL-like queries — including numerical range queries, categorical filters, and Boolean classifiers — on millions of pooled, silica-encapsulated, DNA-barcoded specimens. Demonstrated on 96 mock SARS-CoV-2 genomic samples and human patient-derived nucleic acids, the system avoids cold-chain logistics while enabling complex retrospective epidemiological queries.

## Key Contributions
- Type-aware barcode schema: maps metadata types (Boolean, categorical, numerical) to compact composable barcodes, enabling efficient multi-dimensional queries without exponential barcode count growth
- SQL-like query language: arbitrary logical expressions (AND/OR/NOT, numerical ranges, categorical filters) demonstrated on outbreak scenario
- Room-temperature RNA preservation via 5 µm silica microcapsules; scalable to millions/billions of samples
- High-specificity retrieval: 1 in 10^6 samples recovered in prior Boolean work; type-aware system extends to complex queries
- Human patient-derived nucleic acid storage and sequencing demonstrated — clinically applicable
- Architecture bypasses energy-intensive cold-chain infrastructure (UK Biobank context: ~500,000 samples at −80°C/−180°C)

## Methodology and Architecture
System components:
1. **Encapsulation**: biological specimens (DNA, RNA) in 5 µm silica microcapsules; anoxic protection enables room-temperature RNA storage
2. **Barcoding**: DNA barcode sequences encoding sample metadata; type-aware schema maps field types to barcode sets
3. **Pooling**: all barcoded capsules combined in single pool; high sample density
4. **Query execution**: fluorescence-activated sorting (FAS) using fluorescent probes for barcode detection; parallel biochemical search

Barcoding efficiency: prior systems needed one barcode per value (100 barcodes for ages 0-99); type-aware schema encodes 100 values in ~7 barcodes (log2 scale), enabling age range queries in 2-3 sorting stages instead of 9.

Demonstrated query types on SARS-CoV-2 outbreak scenario (Logan Airport):
- Single health status (e.g., symptomatic)
- Three distinct age ranges
- Simultaneous: date range + location + health status

## Results
- 96 mock patients encoded with: age, vaccination status, symptoms, flight number, month/year, place of origin
- All query types executed successfully with high specificity
- Human patient samples stored and retrieved; sequencing validated
- System scales to millions of samples with maintained fidelity and throughput (parallel biochemical processing vs. sequential robotic retrieval)
- Room-temperature storage eliminates continuous energy consumption and enables point-of-collection sample archiving globally

## Related Papers
- [[computational/fabre-2014-efficient-method-room-temperature]] — foundational Imagene anhydrous capsule RNA storage with quantitative lifetime prediction
- [[computational/colotte-2023-reference-materials-sars-cov-2]] — room-temperature RNA controls for SARS-CoV-2 detection using encapsulation technology
- [[computational/lou-2014-review-room-temperature-storage]] — review of room-temperature biospecimen storage modalities
- [[computational/cardona-ospina-2019-systematic-review-fta-cards]] — FTA cards as alternative room-temperature RNA preservation for fieldwork
