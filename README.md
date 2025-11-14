# Plantation Monitoring using SAM Segmentation and Resnet50

This project implements a practical pipeline for plantation monitoring using the
Segment Anything Model (SAM) for instance/semantic segmentation and a ResNet50
classifier for identifying segmented regions. The SAM model was uploaded and
fine-tuned on domain-specific field imagery to produce accurate crop and
field-category segments. A ResNet50 model was uploaded and subsequently
fine-tuned on labeled segments to classify crop types and distinguish
fallow/other land categories. A lightweight local web interface was developed
to enable interactive upload of field images and visualization of segmentation
and classification outputs. Results (segmentation masks, class labels, and
summary tables) are presented with figures and numeric metrics in the Results
section. 




Monitoring plantations and crop
cover at field level is crucial for agricultural planning, early detection of
crop stress, and estimation of cultivated area. Recent progress in foundation
segmentation models (e.g., SAM) and convolutional neural network classifiers
(e.g., ResNet architectures) enables accurate, automated extraction of crop
regions and their subsequent classification from field imagery. This project
integrates these components into an end-to-end pipeline suitable for
small-scale deployment and interactive use.

Technologies Used

1.      Segment anything model (SAM): Foundation segmentation model used for
producing instance/semantic masks from raw field images.


2.      Resnet50: Convolutional neural network architecture used for
classifying segmented regions into crop types and field categories.


3.      Python ecosystem: Model fine-tuning and inference performed
using Python scripts/notebooks.


4.      Local webpage: simple local web interface to upload field
images, run segmentation + classification, and visualize results.


