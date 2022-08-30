# A Paper List for Relations between Trustworthy AI Concepts

This is a paper list for relations between trustworthy AI concepts, including
- Utility (base)
- OOD Generalization
- Adversarial Robustness
- Privacy
- Fairness
- Explainable
- ...

---

## Utility v.s. OOD Generalization

## Utility v.s. Adversarial Robustness

### Difference between Robustness Generalization & Standard Generalization
- NIPS2018 PAC-learning in the presence of evasion adversaries
- ICML2019 Rademacher Complexity for Adversarially Robust Generalization
- NIPS2018 Adversarially Robust Generalization Requires More Data
- ICLR2020 Adversarially Robust Generalization Just Requires More Unlabeled Data
- ICML2019 Adversarial Examples from Computational Constraints
- COLT2019 VC Classes are Adversarially Robustly Learnable, but Only Improperly

### Tradeoff between Robustness & Utility
- ECCV2018 Is Robustness the Cost of Accuracy? -- A Comprehensive Study on the Robustness of 18 Deep Image Classification Models
- ICLR2019 Robustness May Be at Odds with Accuracy
- NIPS2019 Adversarial Examples Are Not Bugs, They Are Features
- Theoretically Principled Trade-off between Robustness and Accuracy
- Are Accuracy and Robustness Correlated?
- ICML2020 Understanding and Mitigating the Tradeoff Between Robustness and Accuracy
- ICML2019 Adversarial Training Can Hurt Generalization
- The Relationship Between High-Dimensional Geometry and Adversarial Examples
- CVPR2019 Disentangling Adversarial Robustness and Generalization
- Robustness and Accuracy Could Be Reconcilable by (Proper) Definition
- Towards Deep Learning Models Resistant to Adversarial Attacks
- ICML2019 Adversarial Training Can Hurt Generalization
- More Data Can Expand the Generalization Gap Between Adversarially Robust and Standard Models>
- UAI2021 The Curious Case of Adversarially Robust Models: More Data Can Help, Double Descend, or Hurt Generalization
- Adversarial robustness may be at odds with simplicity
- 2020 Precise Tradeoffs in Adversarial Training for Linear Regression
- A Closer Look at Accuracy vs. Robustnes


## Utility v.s. Privacy

## Utility v.s. Fairness

---
## OOD Generalization v.s. Adversarial Robustness

## OOD Generalization v.s. Privacy

## OOD Generalization v.s. Fairness

---

## Robustness v.s. Privacy based on Utility
| Index               | Advsarial Robustness               | Privacy                                          | Relation                                                                              | Theoretical             |
|---------------------|------------------------------------|--------------------------------------------------|---------------------------------------------------------------------------------------|-------------------------|
| 2019 Mejia          | Adversarial Training               | Model Inversion                                  | R can hurt P                                                                          | no       |
| 2019 CCS Song       | Adversarial Training               | Membership Inference                             | R can hurt P                                                                          | no       |
|                     | Verifiable Defenses                |                                                  |                                                                                       |                         |
| 2020 He             | Robustified Intensity              | Differential Privacy                             | R can hurt P                                                                          | yes                     |
|                     | Adversarial Training               |                                                  |                                                                                       |                         |
| 2022 Hayes          | Adversarial Training               | Membership Inference                             | R has both positive and negtive effects on P                                          | yes                     |
| 2021 Tursynbek      | Adversarial Example                | Differential Privacy                             | P has both positive and negtive effects on R                                          | no       |
|                     | Decision Boundary Distance         |                                                  |                                                                                       |                         |
|                     | Curvature Profile                  |                                                  |                                                                                       |                         |
| 2021 Boenisch       | Adversarial Example                | Differential Privacy                             | P has both positive and negtive effects on R, positive effect due to gradient masking | no       |
| 2021 Han            | E-adversarial robustness           | Local Differential Privacy of Federated Learning | P and R are Sufficient and Necessary concepts                                         | yes                     |
|                     | Adversarial Example                |                                                  | P has both positive and negtive effects on R                                          |                         |
| 2019 ECM-PKDD Pinot | Generalized Adversarial Robustness | Renyi-Differential Privacy                       | P and R are Sufficient and Necessary concepts                                         | no |
| 2019 S&P Lecuyer    | Verifiable Defenses                | Pixel-Differential Privacy                       | P methods can transfer to R                                                           | yes                     |
| 2019 CCS Jia        | Adversarial Example                | Membership Inference                             | R methods can transfer to P                                                           | no                      |
| 2019 IJCAI Phan     | Verifiable Defenses                | Differential Privacy                             | Methods for both R and P                                                              | yes                     |
| 2020 ICML Phan      | Verifiable Defenses                | Differential Privacy                             | Methods for both R and P                                                              | yes                     |
| 2022 ICLR Anon      | Adversarial Training               | Differential Privacy                             | Methods for both R and P                                                              | no                      |


## Robustness v.s. Fairness based on Utility

## Privacy v.s. Fairness based on Utility





