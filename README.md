# GSOC-Evaluation24


### Common Test I. Multi-Class Classification

weights: [classification_model.pth](https://drive.google.com/file/d/1c9UipjdKYQyznsY2M7FbdvPbb6U_xRox/view?usp=sharing)

Task: Build a model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy.

Dataset: [Drive](https://drive.google.com/file/d/1ZEyNMEO43u3qhJAwJeBZxFBEYc_pVYZQ/view)

Dataset Description: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 

### Specific Test VI. SSL on Real Dataset

There are Two specific notebooks:

* The main submission notebook can be found here: [SSL_dino](https://github.com/mishra-18/GSOC-Evaluation24/blob/main/SSL/SSL_dinomodel.ipynb)

   Weights: [dino_model_final.pth](https://drive.google.com/file/d/1_pKESS9DmMRUZN8XBuEdoHdW1TQd0Zww/view?usp=sharing)

* The supplementary test Notebook can be found in the same repository [here](https://github.com/mishra-18/GSOC-Evaluation24/blob/main/SSL/dino_model.ipynb)
  Weights: [dino_model_test.pth](https://drive.google.com/file/d/1OTw18pRL1SV99ueDcTHL7iFcknNjv3HK/view?usp=sharing)

Task: Build a Self-Supervised Learning model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy. 

Dataset: [Drive](https://drive.google.com/file/d/1aafE2nDp7S6j59sZcBIzP3FnQxVCmHCx/view)

Dataset Description: The Dataset consists of two classes, strong lensing images with lenses and non-lenses in npy format. For non-lensing images, the images start with nl_. These images are from the Hubble Space Telescope. 
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve). Although the dataset is small and results may not be perfect, the pipeline should be such that with more data, the model could achieve high performance. 
