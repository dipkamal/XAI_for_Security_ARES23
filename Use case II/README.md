# Use-case-II: Malware Classification 

In this notebook, we demonstrate the application of explanation methods in understanding the black-box model prediction on pdf malware classification. We first generate explanations for malware test instances using various 
explanation methods and then evaluate the explanations using quantitative metrics. 

This folder contains following files:
- data: This folder consists of pdf malware data and the trained pytorch model. 
- pdf_classifier_lime_ipynb: This notebook contains evaluation of LIME explanation method. 
- sok_pdf_classifier_evaluation.ipynb: This notebook contains evaluations of SHAP, Occlusion, Gradient, Integrated Gradient, DeepLift, GradientShap. 
