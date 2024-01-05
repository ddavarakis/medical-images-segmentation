# Medical Images Segmentation

### Dataset used

A radiology dataset (<https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database>) that contains chest X-ray scans collected from various hospitals. It contains chest X-ray scans. All the X-ray scans contain a corresponding pixel level annotation of lungs.

### Data preparation
Dataset is split into training, validation, and testing dataset (by using 50%-20%-30%). Training performed on a small subset (30%) of the training dataset due to computing resources unavailability.

### Model training
Two deep learning models, ResUNet and DeConvNet, trained to segment the lungs contained in the X-ray scans. 

### Evaluations
Dice Coefficients used to evaluate segmentation predictions of the trained models. 

### Visualize predicted segmentation masks
In addition to Dice Coefficients, 5-10 sample predicted segmentation masks with their corresponding input image and ground truth annotation mask are visualized (`ImageMasking.ipynb`).
