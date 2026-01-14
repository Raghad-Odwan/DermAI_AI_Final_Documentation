# DermAI – AI Final Documentation

This repository represents the **final documentation and completion reference of the AI component** for the DermAI project.  
It consolidates all AI-related work developed throughout the project lifecycle and presents the finalized results in alignment with **Chapter 3 (Methodology)** and **Chapter 6 (Results)** of the project report.

---

## Repository Purpose
This repository was created to:
- Document the complete AI development pipeline in a structured and reproducible manner.
- Provide a unified reference to all AI repositories developed for DermAI.
- Summarize the final performance of the selected AI model.
- Officially confirm the completion of the AI component within the DermAI system.

---

## AI Development Pipeline
The AI component was developed following a research-driven and clinically oriented workflow:

1. Dataset engineering and preparation  
2. Image quality validation and filtering  
3. Comparative analysis of multiple classification algorithms  
4. Cross-validation to ensure model stability and generalization  
5. Final model training and evaluation  
6. Model explainability using Grad-CAM  

Each phase is documented and mapped to the corresponding sections in the project report.

---

## AI Project Repositories

The following repositories represent **all AI-related work developed for the DermAI project**:

### Dataset Engineering
https://github.com/Raghad-Odwan/DermAI_Dataset  
Contains dataset preparation, preprocessing, and data organization procedures used throughout the project.

### Comparative Algorithms
https://github.com/Raghad-Odwan/DermAI_Comparative_Algorithms  
Includes baseline models and comparative experiments used to evaluate multiple classification architectures.

### Image Validation Module
https://github.com/Raghad-Odwan/Image-Validation-Module-DermAI  
Implements image quality validation and filtering to ensure reliable input data for model training.

### Cross-Validation Training
https://github.com/Raghad-Odwan/DermAI_Training_Cross-validiation-  
Contains the cross-validation training pipeline used to assess model stability and generalization.

### Final Model Training
https://github.com/Raghad-Odwan/DermAI_Final_Training  
Includes the finalized training pipeline and selected model configuration.

### Grad-CAM Explainability
https://github.com/Raghad-Odwan/DermAI_GradCAM-Final-Model  
Provides visual explainability analysis for the final trained model using Grad-CAM techniques.

---

## Final Model Summary
- **Selected Architecture:** ResNet50 (Transfer Learning)  
- **Task:** Skin lesion classification  
- **Evaluation Strategy:** Cross-validation followed by evaluation on a held-out test set  

---

## Final Performance Metrics

The final AI model was evaluated using both validation and held-out test datasets to ensure stable generalization and reliable performance.

- **Accuracy:** 83.7%
- **Sensitivity (Recall – Melanoma):** 73.6%
- **Specificity:** Not explicitly computed in the final evaluation
- **AUC:** Not reported

The close agreement between validation and test results indicates consistent model behavior with minimal overfitting, while maintaining clinically relevant sensitivity for melanoma detection.

---

## Project Status
The AI component of the DermAI system is **complete and finalized**.  
All development stages, experiments, evaluations, and explainability analyses have been successfully conducted and documented.  
The AI module is ready for system integration and deployment.

---

## Notes
This repository focuses on **documentation and summarized results**.  
All datasets, training code, experimental scripts, and model implementations remain available in their respective repositories listed above.
