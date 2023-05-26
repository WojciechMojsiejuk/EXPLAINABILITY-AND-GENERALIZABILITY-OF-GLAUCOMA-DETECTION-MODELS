# EXPLAINABILITY-AND-GENERALIZABILITY-OF-GLAUCOMA-DETECTION-MODELS
Master's Thesis Materials
[![DOI](https://zenodo.org/badge/645783799.svg)](https://zenodo.org/badge/latestdoi/645783799)

## How to navigate a project:

### [Models reproducibility on ACRIMA and ORIGA datasets and XAI tools setup](./xai.ipynb)
![classification_report](https://github.com/WojciechMojsiejuk/EXPLAINABILITY-AND-GENERALIZABILITY-OF-GLAUCOMA-DETECTION-MODELS/assets/24994240/9204365c-79ca-40cf-a27b-d67d65ba4b01)

### [Results of Diaz-Pinto models](./results)

### [Set up of models trained on RIM ONE DL dataset](./rimone.ipynb)

![r50rimonecm](https://github.com/WojciechMojsiejuk/EXPLAINABILITY-AND-GENERALIZABILITY-OF-GLAUCOMA-DETECTION-MODELS/assets/24994240/4d1cd063-c5a9-40a8-aa11-6fffe79be186)

### [Results of Fumero models](./results_RIMONE)

### [Example-based explaination](./best_examples.ipynb)

![best_healthy_corr](https://github.com/WojciechMojsiejuk/EXPLAINABILITY-AND-GENERALIZABILITY-OF-GLAUCOMA-DETECTION-MODELS/assets/24994240/169c212e-d1e3-45fd-b22e-e01e31aa1b6b)

### [GradCAM analysis](./gradcam.ipynb)

![xgrad1](https://github.com/WojciechMojsiejuk/EXPLAINABILITY-AND-GENERALIZABILITY-OF-GLAUCOMA-DETECTION-MODELS/assets/24994240/e76a72a8-6cb7-4481-b3cc-a7b3961ce211)

## Datasets

[ACRIMA](https://figshare.com/articles/dataset/CNNs_for_Automatic_Glaucoma_Assessment_using_Fundus_Images_An_Extensive_Validation/7613135)

[RIM ONE DL](https://github.com/miag-ull/rim-one-dl)

[High-Resolution Fundus (HRF) Image Database](https://www5.cs.fau.de/research/data/fundus-images/)

[BEH (Bangladesh Eye Hospital) Dataset](https://github.com/mirtanvirislam/Deep-Learning-Based-Glaucoma-Detection-with-Cropped-Optic-Cup-and-Disc-and-Blood-Vessel-Segmentation/tree/master/Dataset)

## Tech stack

- Python
- Numpy
- Pandas
- Keras & Tensorflow
- PIL
- OpenCV
- Scikit-learn
- Scipy
- Matplotlib
- tf-explain
