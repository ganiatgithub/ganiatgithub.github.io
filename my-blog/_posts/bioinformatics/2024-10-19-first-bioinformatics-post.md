---
layout: post
title: "Exploring OTU Analysis with Vegan in R"
date: 2024-10-19
categories: bioinformatics
---

In this post, I discuss how to process OTU tables using the `vegan` package in R to estimate species richness and diversity.

```R
library(vegan)
data(dune)
richness <- specnumber(dune)
print(richness)
```