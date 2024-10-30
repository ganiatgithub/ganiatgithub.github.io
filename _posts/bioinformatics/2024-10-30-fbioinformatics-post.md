---
layout: post
title: "Fishing the right gene"
date: 2024-10-30
categories: bioinformatics
---

# Introduction
What's all these fuzz about precision therapy? How do we know exactly what genes to target?

Genome holds an incredible wealth of information, much like a vast ocean waiting to be explored. Unlocking these insights can seem overwhelming without the right approach. But if we can visualise genome, we are much closer to identify target genes.

# What do we have?

In this study, we aim to understand how two gene families are regulated—in other words, how their expression is controlled by other genetic elements. 

To answer this question, we first reconstructed genomes using high-throughput sequencing methods. Next, we annotated (i.e., assigned functions to) the genes. This was followed by visualising the genetic arrangement of key genes using a systematic approach.

Since we are particularly interested in the regulation of <span style="color: red;">gene family A</span> and <span style="color: red;">gene family B</span>, we identified both upstream and downstream genes adjacent to these gene families, in order to gain clues about potential regulators.

![figure](/assets/images/bioinformatics/gene_organisation_example.png)

We found that the <span style="color: red;">regulator gene x</span> appears to regulate both gene families. Additionally, we identified a diverse range of other genes associated with both gene families. These genes are probably important as well, though their specific roles are yet to be determined.

## Implication

By understanding how genes are regulated, we can devise innovative ways to interfere with their expression, thereby engineering specific physiological traits. If a gene promotes health (e.g., by enhancing human well-being), we should probably do our best to keep it.

Now, the question for you, if a gene has harmful effects, what shall we do?
