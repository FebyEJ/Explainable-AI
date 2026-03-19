# XAI on a VGG-16 ASL (American Sign Language) Classifier:

This project implements Explainable Artificial Intelligence (XAI) on a VGG-16 model used for American Sign Language (ASL) classification, using multiple XAI techniques such as  Local Interpretable Model-Agnostic Explanations (LIME), Gradient-weighted Class Activation Mapping (GradCAM), Layer-wise Propagation (LRP), Contextual Relevance Propagation (CRP), Integrated Gradients, and Occlusion Sensitivity to analyze
and visualize the model's decisions. The ASL dataset, consisting of 36 sign classes (A-Z, 0-9), is used for training and evaluation. We evaluate the model’s performance on an ASL dataset with accuracy and explainability metrics. The VGG-16 model achieves a classification accuracy of 83.33%.

**Contributions of this project:**
* Development of a VGG-16-based ASL classification model, achieving high accuracy in recognizing 36 ASL hand gestures (A-Z, 0-9).
* Implementation of multiple XAI techniques (LIME, Grad-CAM, Occlusion Sensitivity, Integrated Gradients, LRP, and CRP) to analyze and explain model predictions.
* Comparison of XAI methods based on qualitative visualization.
* Evaluation of model performance in terms of accuracy, confusion matrices, and XAI-generated insights.
