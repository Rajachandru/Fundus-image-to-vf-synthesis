# Fundus-image-to-vf-synthesis
fundus to vf synthesis project
## Objectives

- Develop a deep learning-based system to synthesize Visual Field (VF) data from fundus images.  
- Bridge the structural–functional gap in glaucoma diagnosis by predicting VF from easily acquired fundus images.  
- Design and evaluate multiple model variations using advanced loss functions and optimization techniques (contrastive loss, reliability weighting, PSO).  
- Leverage multimodal data (Fundus images, Visual Field data, and Intraocular Pressure) to improve prediction accuracy.  
- Analyze and compare model performance using evaluation metrics such as MSE.  
- Build a prototype pipeline that can support future clinical applications for glaucoma monitoring.  

---

## Experiments (Multiple Models)

This project explores several model variants for fundus-to-visual-field synthesis:

- **Base Model for VF Synthesis** → ViT + CDPM with conventional loss  
- **Model with Reliability Weights** → ViT + CDPM with reliability-weighted loss  
- **Model with Contrastive Loss** → ViT + CDPM with contrastive loss  
- **Model with PSO Optimization** → ViT + CDPM with optimized parameters (PSO)  
- **Model with only optimized parameters** → ViT + CDPM with manually tuned parameters  
- **Pretrained Model** → ViT + CDPM for inference/testing only  

---

## Files

- `base_model_for_vf_synthesis.ipynb` → Base Model for VF Synthesis  
- `model_with_reliability_weights.ipynb` → Model with Reliability Weights  
- `model_with_contrastive_loss.ipynb` → Model with Contrastive Loss  
- `model_with_pso_optimization.ipynb` → Model with PSO Optimization  
- `model_with_only_optimized_parameters.ipynb` → Model with only optimized parameters  
- `pretrained_model.ipynb` → Pretrained Model  

---

## Outputs

| Model | Objective | Algorithm |
|-------|----------|-----------|
| Base Model for VF Synthesis | VF synthesis from fundus image | ViT + CDPM with conventional loss |
| Model with Reliability Weights | VF synthesis from fundus image | ViT + CDPM with reliability-weighted loss |
| Model with Contrastive Loss | VF synthesis from fundus image | ViT + CDPM with contrastive loss |
| Model with PSO Optimization | VF synthesis from fundus image | ViT + CDPM with optimized parameters (PSO) |
| Model with only optimized parameters | VF synthesis from fundus image | ViT + CDPM with manually tuned parameters |
| Pretrained Model | VF synthesis from fundus image | ViT + CDPM for inference/testing only |

---
#result

 # sample output
 https://github.com/Rajachandru/Fundus-image-to-vf-synthesis/blob/df9b27f3c771ba43acfdc046629e9773048222e8/sample_output.png

 
