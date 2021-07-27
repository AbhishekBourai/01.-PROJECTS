Skin Cancer Classification - Multi Class Image Classification using CNN
=========================================================================


**Skin cancer** is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopic analysis, a biopsy and histopathological examination. Automated classification of skin lesions using images is a challenging task owing to the fine-grained variability in the appearance of skin lesions.

This the **HAM10000 ("Human Against Machine with 10000 training images") dataset**.It consists of **10015 dermatoscopicimages** which are released as a training set for academic machine learning purposes and are publiclyavailable through the ISIC archive. This benchmark dataset can be used for machine learning and for comparisons with human experts.

It has **7 different classes** of skin cancer which are listed below :
1. Melanocytic nevi
2. Melanoma
3. Benign keratosis-like lesions
4. Basal cell carcinoma
5. Actinic keratoses
6. Vascular lesions
7. Dermatofibroma

In this kernel I will try to **detect 7 different classes of skin cancer using Convolution Neural Network with keras tensorflow in backend** and then analyse the result to see how the model can be useful in practical scenario.
We will move step by step process to classify 7 classes of cancer.

**In this kernel I have followed following steps for model building and evaluation which are as follows :
- Step 1 : Importing Essential Libraries
- Step 2: Making Dictionary of images and labels
- Step 3: Reading and Processing Data
- Step 4: Data Cleaning
- Step 5: Exploratory data analysis (EDA)
- Step 6: Loading & Resizing of images
- Step 7: Train Test Split
- Step 8: Normalization
- Step 9: Label Encoding
- Step 10: Train validation split
- Step 11: Model Building (CNN)
- Step 12: Setting Optimizer & Annealing
- Step 13: Fitting the model
- Step 14: Model Evaluation (Testing and validation accuracy, confusion matrix, analysis of misclassified instances)

