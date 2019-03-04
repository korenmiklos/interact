---
title: Buyer-supplier interaction and the gains from outsourcing
author: Miklós Koren
navigation: empty

---

## Motivation
- Digitization and the internet can reshape B2B communication and interaction.
- Aggregate productivity gains from digital technologies are still modest.
- Superstar firms increasingly dominate in the economy.

## Research questions
1. How does interaction between firms affect aggregate productivity?
2. Does interaction benefit some firms more than others?
3. How does technical change reshape firm-to-firm interaction?

## Theory 
Build a quantifiable aggregative model with buyer-supplier _wedges_.

Agnostic about sources of wedges:

- search frictions
- network links
- geographical distance

## Measurement 
Estimate exactly-identified wedges on 

- B2B transactions data from VAT filings
- communication patterns from a large firm

Account for sparsity

Counterfactuals

## Production function
$$
	Q_{i} = \left[
		\sum_{j=1}^N (\kappa_{ij}M_{ij})^{1-1/\theta}
		\right]^{\theta/(\theta-1)},
$$

$M_{ij}$: purchases from firm $j$. $M_{ii}$: in-house value added. $\kappa_{ij}\ge 0$: interaction efficiency ("wedge").

## What are the wedges?

**network structure**: $\kappa_{ij} \in \{0,1\}$. $2^{N^2}$ possibilities.

**economic geography**: $\kappa_{ij}=e^{-\tau d_{ij}}$. Dimensionality: $2\times N$.

**this paper**: Let the data speak.

## Estimation
needed: 

- formula for $\kappa_{ij}$
- formula for "gains from outsourcing"

## Counterfactuals


## Future studies
