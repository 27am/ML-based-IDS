# An open Machine Learning based Intrusion Detection System

Our aim has been to evaluate Machine Learning techniques, in particular:
- Feedforward NN
- Convolutional NN
- Random Forest
and their performances as Intrusion Detection Systems, related to an Architecture development. 

Notoriously, cybersecurity is a challenging environment for strict limitation both in False Positives and False Negatives rates, moreover taking into account Zero Days attacks. Supervised learning algorithms aren't natively well suited for such tasks. At the same time, an Anomaly Detection approach presents difficulties to model efficiently multivaried data where choosing the appropriate threshold becomes a critical parameter.

We propose a Two-Tiered architecture, one part deployed in the Cloud consisting in training online models (and taking advantage of integrated Data Lakes) and the other Edge side where models are pushed and deployed for local classification. Suspicious traffic is relayed in the Cloud for deeper analysis, model update and new deployment; this generates a loop architecures that learns and improves iteratively.
