# Neonatal-Signal-Suppression-CV
### Adopting Endocrine Inhibition Logic for Deep Learning

This repository implements a novel training constraint based on the research by **Park et al. (2024)[cite_start]**.
"Inhibition of testicular development by suppressing neonatal LH rise in male domestic pigs"
(Park et al., Animal Reproduction Science, 2024)

##  Biological Inspiration
In male domestic pigs, suppressing the neonatal LH rise leads to the inhibition of testicular development. We apply this logic to **Deep Learning** by suppressing "Signal Surges" in the neonatal (early) phase of model training to prevent the development of biased or redundant feature representations.

## Key Mechanisms
* **LH-Rise Metaphor**: Identifying early training gradients that define model "maturity."
* [cite_start]**E2+TBA Regularization**: An adversarial penalty that mimics the hormonal implant used to suppress LH secretion.
* **Architectural Inhibition**: Preventing the "growth" of specific network branches to ensure a more generalized, unbiased final state.

