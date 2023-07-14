# GALA
Official Repository for the MICCAI 2023 paper titled Geometry-adaptive Network for Robust Detection of Placenta Accreta Spectrum Disorders

# Abstract
Placenta accreta spectrum (PAS) is a high-risk obstetric disorder associated with significant morbidity and mortality. Since the abnormal invasion usually occurs near the uteroplacental interface, there is a large geometry variation in the lesion bounding boxes, which considerably degrades the detection performance. In addition, due to the confounding visual representations of PAS, the diagnosis highly depends on the clinical experience of radiologists, which easily results in inaccurate bounding box annotations. In this paper, we propose a geometryadaptive network for robust PAS detection. Specifically, to deal with the geometric prior missing problem, we design a Geometry-adaptive Label Assignment (GA-LA) strategy and a Geometry-adaptive RoI Fusion (GA-RF) module. The GA-LA strategy dynamically selects positive PAS candidates (RoIs) for each lesion according to its shape information. The GA-RF module aggregates the multi-scale RoI features based on the geometry distribution of proposals. Moreover, we develop a Lesion-aware Detection Head (LA-Head) to leverage high-quality predictions to iteratively refine inaccurate annotations with a novel multiple instance learning paradigm. Experimental results under both clean and noisy labels indicate that our method achieves state-of-the-art performance and demonstrate promising assistance for PAS diagnosis in clinical applications.

# Model Structure
![image](https://github.com/Meteorary/GALA/blob/main/pics/structure.png)

![image](https://github.com/Meteorary/GALA/blob/main/pics/visualizations.png)
