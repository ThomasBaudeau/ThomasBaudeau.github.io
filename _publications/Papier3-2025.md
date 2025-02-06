---
title: "Assessing Long-Read Mappers for Viral Genomics"
collection: publications
category: preprint
permalink: /publication/Papier3-2025
excerpt: ''
date: 2024-11-25
venue: 'PCI Genomic'
citation: 'Thomas Baudeau, Camille Marchet, Mikaël Salson. (2024). &quot;Assessing Long-Read Mappers for Viral Genomics.&quot; <i>PCI Genomic</i>.'
---

Long-read sequencing technologies from Pacific Biosciences and Oxford Nanopore Technologies (ONT) have advanced genomic
research, producing reads over 10 kilobases and enabling rapid field-based viral surveillance. This study evaluates eight long-read
mapping tools on viral genomic data, including modern and legacy methods. We assessed their performance on ONT reads and
their impact on variant calling using bcftools and medaka. Using simulated and real datasets under varying conditions, reflecting
different experimental and biological conditions, such as variable read lengths, error rates and the presence of multiple viral vari-
ants, we found that the majority of tools had great difficulty in correctly managing read edges. In addition, it was found that with a
default setting, the performance of the tools decreased