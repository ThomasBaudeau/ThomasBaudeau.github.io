---
title: "Improved sub-genomic RNA prediction with the ARTIC protocol "
collection: publications
category: manuscripts
doi: https://doi.org/10.1093/nar/gkae687
permalink: /publication/Papier2-2024
excerpt: ''
date: 2024-09-21
venue: 'Nucleic Acids Research'
citation: 'Thomas Baudeau ,Kristoffer Sahlin. &quot;Improved sub-genomic RNA prediction with the ARTIC protocol; <i>Nucleic Acids Research</i>.'
---

Viral subgenomic RNA (sgRNA) plays a major role in SARS-COV2’s replication, pathogenicity, and evolution. Recent sequencing protocols, such as the ARTIC protocol, have been established. However, due to the viral-specific biological processes, analyzing sgRNA through viral-specific read sequencing data is a computational challenge. Current methods rely on computational tools designed for eukaryote genomes, resulting in a gap in the tools designed specifically for sgRNA detection. To address this, we make two contributions. Firstly, we present sgENERATE, an evaluation pipeline to study the accuracy and efficacy of sgRNA detection tools using the popular ARTIC sequencing protocol. Using sgENERATE, we evaluate periscope, a recently introduced tool that detects sgRNA from ARTIC sequencing data. We find that periscope has biased predictions and high computational costs. Secondly, using the information produced from sgENERATE, we redesign the algorithm in periscope to use multiple references from canonical sgRNAs to mitigate alignment issues and improve sgRNA and non-canonical sgRNA detection. We evaluate periscope and our algorithm, periscope_multi, on simulated and biological sequencing datasets and demonstrate periscope_multi’s enhanced sgRNA detection accuracy. Our contribution advances tools for studying viral sgRNA, paving the way for more accurate and efficient analyses in the context of viral RNA discovery.