# Transductive Adversarial Networks (TAN)
Code for the paper "Transductive Adversarial Networks (TAN)" by Sean Rowan<sup>1</sup> (2018).

The paper is available at: https://arxiv.org/abs/1802.02798

---

ABSTRACT -- Transductive Adversarial Networks (TAN) is a novel domain-adaptation machine learning framework that is designed for learning a conditional probability distribution on unlabelled input data in a target domain, while also only having access to: (1) easily obtained labelled data from a related source domain, which may have a different conditional probability distribution than the target domain, and (2) a marginalised prior distribution on the labels for the target domain. TAN leverages a fully adversarial training procedure and a unique generator/encoder architecture which approximates the transductive combination of the available source- and target-domain data. A benefit of TAN is that it allows the distance between the source- and target-domain label-vector marginal probability distributions to be greater than 0 (i.e. different tasks across the source and target domains) whereas other domain-adaptation algorithms require this distance to equal 0 (i.e. a single task across the source and target domains). TAN can, however, still handle the latter case and is a more generalised approach to this case. Another benefit of TAN is that due to being a fully adversarial algorithm, it has the potential to accurately approximate highly complex distributions. Theoretical analysis demonstrates the viability of the TAN framework.

---

<sup>1</sup>University College London. Correspondence to: <sean.rowan.16@ucl.ac.uk>.