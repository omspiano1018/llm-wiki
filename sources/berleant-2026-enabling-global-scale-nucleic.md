---
title: "Enabling Global-Scale Nucleic Acid Repositories Through Versatile, Scalable Biochemical Selection from Room-Temperature Archives"
authors: Joseph D. Berleant, James L. Banal, Dhriti K. Rao, Mark Bathe
year: 2026
doi: 10.1038/s41467-026-69402-3
category: computational
pdf_path: C:/Users/User/Desktop/llm-wiki/papers/Enabling global-scale nucleic acid repositories through versatile, scalable biochemical selection from room-temperature archives.pdf
pdf_filename: Enabling global-scale nucleic acid repositories through versatile, scalable biochemical selection from room-temperature archives.pdf
source_collection: external
---

## One-line Summary
A scalable room-temperature nucleic acid biobank system using silica-encapsulated, DNA-barcoded, and pooled specimens with SQL-like database queries (numerical ranges, categorical filters, Boolean) demonstrated on 96 mock SARS-CoV-2 samples including human patient-derived nucleic acids.

## 1. Document Information
- **Title**: Enabling Global-Scale Nucleic Acid Repositories Through Versatile, Scalable Biochemical Selection from Room-Temperature Archives
- **Authors**: Joseph D. Berleant, James L. Banal, Dhriti K. Rao, Mark Bathe
- **Year**: 2026
- **Journal**: Nature Communications, vol. 17, article 2807
- **DOI**: 10.1038/s41467-026-69402-3
- **Affiliations**: Department of Biological Engineering, MIT; University of Cambridge; Broad Institute of MIT and Harvard

## 2. Key Contributions
- First demonstration of SQL-like database queries on pooled biological samples: numerical range queries, categorical filters, and Boolean classifiers for nucleic acid biosample retrieval
- Advances beyond prior single-sample retrieval and Boolean-only barcoding systems to support arbitrary logical expressions
- Type-aware barcode schema: maps each metadata field to compact, composable set of barcodes (vs. one barcode per value in prior systems); enables numerical ranges efficiently
- Room-temperature preservation via 5 µm silica microcapsules eliminates cold-chain dependency for RNA samples
- Scalable to millions/billions of samples without loss of fidelity or throughput
- Demonstrated on 96 mock SARS-CoV-2 genomic samples encoding age, vaccination status, symptoms, and flight information; also validated with human patient-derived nucleic acids

## 3. Methodology and Architecture
- Sample architecture: individual nucleic acid specimens (mock SARS-CoV-2 genomes or human samples) encapsulated in 5 µm silica microcapsules; each capsule barcoded with DNA sequences encoding metadata
- DNA barcode schema: type-aware (Boolean, categorical, numerical range); compact binary encoding
  - Boolean: 1 barcode per binary attribute (e.g., symptomatic/asymptomatic)
  - Categorical: compact encoding for discrete categories (e.g., city/country)
  - Numerical range: binary or Gray-code-like encoding of numeric values (e.g., age 0-99 encoded in log-scale number of barcodes)
- Biochemical retrieval: fluorescence-activated sorting (FAS) using fluorescent probes for barcode detection; parallel processing of entire pooled sample
- Prior limitations: 25 barcode sequences for 100 age values would require 9 sorting stages for a 50-74 age range; new type-aware schema dramatically reduces stages
- Human patient-derived nucleic acids: clinical genomic analysis demonstrated, illustrating applicability beyond mock samples
- Context: UK Biobank has ~500,000 samples at −80°C/−180°C; present work targets much larger-scale systems without continuous energy consumption

## 4. Key Results and Benchmarks
- 96 mock patient samples encoded with multi-dimensional metadata (age, location, vaccination status, flight number, month/year, symptoms)
- Multi-attribute queries demonstrated: single health status, three age ranges, simultaneous date range + location + health status
- General-purpose SQL-like query language implemented; arbitrary logical expressions supported
- High-specificity retrieval: target samples comprising 1 in 10^6 of pool recovered with high fidelity (based on prior Boolean system; extended to type-aware)
- Room-temperature storage with silica encapsulation demonstrated to preserve RNA long-term (building on prior Banal/Bathe work)
- Scalability analysis: system architecture supports millions to billions of pooled samples

## 5. Limitations and Future Work
- Fluorescence-activated sorting stages still required; throughput limited by sorting speed
- Silica encapsulation: RNA stability at room temperature demonstrated but long-term (years) performance of patient-derived RNA requires ongoing validation
- Metadata encoding in DNA barcodes adds complexity to sample preparation workflow
- Cost of DNA barcode synthesis per sample needs to be reduced for population-scale deployment
- Future: integration with long-read sequencing platforms; expansion to include epigenomic marks and RNA modifications; deployment in LMIC settings

## 6. Related Work
- Banal and Bathe prior work: silica-encapsulated biosample pooling with Boolean barcode retrieval
- Fabre et al. (2014): quantitative lifetime prediction for room-temperature RNA storage
- Colotte et al. (2023): validation of room-temperature RNA controls (Imagene technology)
- UK Biobank: large-scale frozen biorepository; context for scale goals
- DNA data storage literature: precedents for high-density molecular information storage

## 7. Glossary
- **Silica microcapsule**: 5 µm diameter silica particle encapsulating nucleic acid biosample; protects RNA from degradation at room temperature
- **DNA barcode**: Short DNA sequence encoding metadata about a biological sample; enables selective retrieval from pooled samples
- **Type-aware schema**: Barcode design system mapping different data types (Boolean, categorical, numerical) to compact barcode sets
- **Fluorescence-activated sorting (FAS)**: Fluorescent probe-based sorting of microcapsules; enables parallel retrieval from large pools
- **SQL-like query language**: Structured query language analogous to database queries; supports AND/OR/NOT, ranges, categories
- **Boolean classifier**: Simple binary metadata attribute (e.g., infected/not infected, vaccinated/not vaccinated)
- **Cold chain**: Temperature-controlled supply chain for biological samples (typically −80°C to 2-8°C); costly and energy-intensive
- **Pooled sample database**: Repository where multiple barcoded samples are combined in a single tube/container; retrieval via molecular selection
