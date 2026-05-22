# Detection and Phylogenetic Analysis of Gammacoronavirus Using Oxford Nanopore Sequencing

## Overview
This repository contains documentation and bioinformatics analysis of Gammacoronavirus detected from bat samples using Nested PCR targeting the RdRp gene and Oxford Nanopore Technology (ONT). The project focuses on phylogenetic characterization and zoonotic surveillance through real-time genomic sequencing.

---

## Background
Zoonotic diseases are a major global health concern because more than 75% of emerging infectious diseases originate from wildlife. Bats are recognized as important natural reservoirs of coronaviruses due to their unique immune systems that allow viral persistence without severe clinical symptoms.

Sulawesi, Indonesia, is considered a zoonotic hotspot because of the high overlap between bat habitats and human settlements. Wildlife consumption practices may increase the risk of coronavirus spillover and cross-species transmission.

Oxford Nanopore Technology (ONT) was used in this study because it enables rapid, portable, and real-time sequencing for pathogen surveillance in the field.

---

## Objectives
- Evaluate the effectiveness of Oxford Nanopore Technology (ONT) in viral genome characterization
- Analyze phylogenetic relationships among Gammacoronavirus sequences
- Support genomic surveillance of zoonotic pathogens
- Understand evolutionary relationships between detected viral isolates

---

## Research Information

| Category | Description |
|---|---|
| Research Topic | Evolutionary Bioinformatics & Phylogenetics |
| Institution | Faculty of Biology, Universitas Gadjah Mada |
| Research Location | BRIN Cibinong, Bogor, Indonesia |
| Research Date | July 8, 2025 |
| Sequencing Platform | Oxford Nanopore MinION |
| Target Gene | RdRp (RNA-dependent RNA polymerase) |

---

## Team Members
- Amila Rahima Husna (22/504420/BI/11120)
- Agnesia Elovani (23/521193/BI/11340)
- Citra Nur Rohmatun (23/520732/BI/11330)
- Calvin Wijaya Marbun (23/521401/BI/11345)
- Gadiza Larasayu Ginantika (23/521879/BI/11360)

---

## Methods

### Sample Preparation
Bat sample NS1572 was processed using Nested PCR targeting the RdRp gene.

### Sequencing
Sequencing was performed using:
- Oxford Nanopore Technology (ONT)
- MinION device
- Rapid Barcoding Kit

### Bioinformatics Pipeline
1. FASTQ upload to CZ ID
2. Quality control and adapter trimming
3. Genome assembly
4. MultiBLAST analysis
5. Taxonomic identification
6. Phylogenetic tree construction using MEGA12

### Phylogenetic Analysis
- Method: Neighbor-Joining (NJ)
- Bootstrap: 1000 replicates
- Model: Poisson correction
- Amino acid positions analyzed: 363

---

## Results

Phylogenetic analysis showed that:
- Three Mexico Gammacoronavirus isolates clustered in the same clade
- Bootstrap values reached 99–100%, indicating strong evolutionary relationships
- Infectious bronchitis virus from Indonesia was still classified within Gammacoronavirus but located in a separate branch
- Tobamovirus isolate was positioned far from the Gammacoronavirus clade and used as an outgroup

These findings indicate genetic diversity among Gammacoronavirus isolates and support the importance of continuous molecular surveillance.

---

## Phylogenetic Tree

<img width="900" alt="Phylogenetic Tree" src="figures/hasil_aligment_minpro_fiks.png">

---

## Importance of ONT in Zoonotic Surveillance
Oxford Nanopore Technology provides:
- Real-time sequencing
- Portable field-based pathogen detection
- Faster turnaround time
- Lower sequencing cost
- Flexible multiplex sequencing

ONT combined with bioinformatics analysis can function as an early warning system for emerging zoonotic pathogens.

---

## Repository Structure

```bash
gammacoronavirus-ont-phylogenetic-analysis/
│
├── README.md
├── data/
├── figures/
├── results/
├── docs/
└── references/
