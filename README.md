# Transductive Adversarial Networks (TAN)
PyTorch and LaTeX Code for the paper "Transductive Adversarial Networks (TAN)" by Sean Rowan<sup>1</sup> and Lewis Moffat<sup>1</sup> (2018).

---

ABSTRACT -- TAN is a novel domain-adaptive semi-supervised machine learning framework that is designed for learning a conditional probability distribution on unlabelled data in a target domain, while only having access to: (1) easily obtained labelled data in a related, yet likely simpler, source domain and (2) a prior distribution on the labels for the target domain. TAN leverages a fully adversarial training procedure and a unique generator/encoder architecture which approximates the transductive combination of the source- and target-domain data. A benefit of TAN is that it allows the distance between the source- and target-domain label vector distributions to be greater than 0 whereas other domain-adaptive semi-supervised learning algorithms require this distance to equal 0. TAN can, however, still handle the latter case and is a more generalised approach to this case. Another benefit of TAN is that due to being a fully adversarial algorithm, it has the ability to accurately approximate highly complex distributions. Theoretical and experimental analyses demonstrate the viability of the TAN framework.

---

<sup>1</sup>University College London. Correspondence to: Sean Rowan <sean.rowan.16@ucl.ac.uk>, Lewis Moffat <lewis.moffat@cs.ucl.ac.uk>.