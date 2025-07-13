# XAI-project

This project explores and evaluates explainability methods for image classification using a semantically grounded approach.
Each image is segmented into meaningful parts (e.g., head, tail, ears) using Grounded-SAM, and attribution methods are applied over these regions instead of raw pixels or superpixels.
We integrate gradient-based (e.g., Integrated Gradients, Grad-CAM) and perturbation-based (LIME, Kernel SHAP) explainers, all operating on the same set of interpretable masks.
To evaluate them, we compute a set of metrics that capture different aspects of explainability:
Effective Compactness
Sufficiency Score
Rank Quality Index (RQI)
Valley Score
Stability
The framework is designed to be model-agnostic, semantically coherent, and suitable for benchmarking explainers under a unified evaluation setup.

-final_notebook.ipynb contains the entire code for alle experiments.
-single_instance.ipynb contains the code and the output as a single instance example.

Developed by Mattia Viglino, Vincenzo Montana and Anna Lisa Maddaloni as part of the Explainable AI course at Politecnico di Torino 2025.
