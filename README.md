# Medical Image Analysis

Projects from the Medical Image Analysis course (COMP448) at Koç University, 2025, built in PyTorch.

| Project | What it does
|---|---
| [`mammography-classification/`](mammography-classification) | Classifies CBIS-DDSM mammograms as benign, malignant or benign-without-callback; compares a simple CNN, ResNet50, a U-Net encoder and a Swin Transformer with 5-fold cross-validation and paired statistical tests (best validation F1: ResNet50, 0.55). Term project.
| [`unet-segmentation/`](unet-segmentation) | U-Net image segmentation (test F1 0.84) with experiments on network depth, feature channels and dropout rate.
| [`skin-lesion-classification/`](skin-lesion-classification) | Skin lesion classification on DermaMNIST with class-weighted loss and augmentation; hyperparameter tuning study (best validation accuracy 0.69). Notebook only.
| [`diabetic-retinopathy-survey.pdf`](diabetic-retinopathy-survey.pdf) | Literature survey comparing 2D fundus and 3D imaging approaches for deep-learning-based diabetic retinopathy detection. 

Datasets are not included; see each report for sources.
