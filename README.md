# svmbonefracture
Identification of Human Bone Fractures from X-Ray Images Using SVM


Objective: 
Evaluate Support Vector Machine (SVM) classification models to distinguish between fractured and non-fractured bone X-ray images with high accuracy.

Dataset: 
Utilized the Fracture Multi-Region X-ray Data from Kaggle, comprising 10,580 human bone X-ray images categorized into fractured and non-fractured classes. The dataset includes 9,246 images for training, 828 for validation, and 506 for testing.  Dataset link here: https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data.

Methods: 
Preprocessed X-ray images by converting them to grayscale and resizing to 150 x 150 pixels. Flattened the images into one-dimensional vectors. Applied SVM with various kernels (RBF, Linear, Poly, Sigmoid) for classification.

Results: 
- RBF Kernel: Achieved 95% accuracy.
- Linear Kernel: Achieved 100% accuracy.
- Poly Kernel: Achieved 98% accuracy.
- Sigmoid Kernel: Achieved 52% accuracy.
- 
 Conclusion: SVM models, especially with Linear and Poly kernels, demonstrated high accuracy (up to 100%) in distinguishing between fractured and non-fractured bone X-ray images. This indicates SVM's potential as an efficient diagnostic tool for rapid and accurate fracture identification in X-ray images.
