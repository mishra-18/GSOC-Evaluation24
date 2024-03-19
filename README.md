# GSOC-Evaluation24


Common Test I. Multi-Class Classification
weights: [classification_model.pth](https://drive.google.com/file/d/1c9UipjdKYQyznsY2M7FbdvPbb6U_xRox/view?usp=sharing)

Task: Build a model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy.

Dataset: [Drive](https://drive.google.com/file/d/1ZEyNMEO43u3qhJAwJeBZxFBEYc_pVYZQ/view)

Dataset Description: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 

Specific Test VI. SSL on Real Dataset
Weights: [dino_model](https://drive.google.com/file/d/1NEniPHl9Q-89L5E6NLm2mOWm1LPAzBZX/view?usp=sharing)

Task: Build a Self-Supervised Learning model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy. 

Dataset: [Drive](https://drive.google.com/file/d/1aafE2nDp7S6j59sZcBIzP3FnQxVCmHCx/view)

Dataset Description: The Dataset consists of two classes, strong lensing images with lenses and non-lenses in npy format. For non-lensing images, the images start with nl_. These images are from the Hubble Space Telescope. 
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve). Although the dataset is small and results may not be perfect, the pipeline should be such that with more data, the model could achieve high performance. 
