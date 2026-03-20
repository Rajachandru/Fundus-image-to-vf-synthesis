# Fundus-image-to-vf-synthesis
fundus to vf synthesis project

## Objectives

 To develop a deep learning-based system for synthesizing Visual Field (VF) data from fundus images.
 To bridge the structural-functional gap in glaucoma diagnosis by predicting VF from easily acquired fundus images.
 To design and evaluate multiple model variations using different loss functions and optimization techniques (contrastive loss, reliability weighting, PSO).
 To utilize multimodal datasets (Fundus, Visual Field, and Intraocular Pressure) for improved prediction accuracy.
 To analyze and compare model performance using evaluation metrics such as MSE.
 To build a prototype pipeline that can support future development of a clinical application for glaucoma monitoring.

 ## Experiments(multiple model)

This project explores multiple approaches for fundus-to-visual-field synthesis:

 **Base Model** → Initial implementation
 **Contrastive Loss Model** → Improved feature learning using contrastive loss
 **Reliability Weight Model** → Weighted training based on reliability
 **PSO Model** → Optimization using Particle Swarm Optimization
 **Without PSO Model** → Baseline comparison without optimization
 **Pretrained Model** → Inference using pretrained weights

## Files

 `basemodel for vf synthesis.ipynb` → Base model
 `grape_cdpm_with_contrastive.ipynb` → Contrastive loss
 `reliability weight for vf synthesis.ipynb` → Reliability weighting
 `vf synthesis with pso.ipynb` → PSO optimization
 `vf synthesis_without_pso.ipynb` → Without PSO
 `pretrained model for vf synthesis.ipynb` → Pretrained inference


#result

 # sample output
 https://github.com/Rajachandru/Fundus-image-to-vf-synthesis/blob/df9b27f3c771ba43acfdc046629e9773048222e8/sample_output.png

 
