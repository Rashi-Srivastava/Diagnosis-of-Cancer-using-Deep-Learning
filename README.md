# Diagnosis-of-Cancer-using-Deep-Learning
Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma
(IDC) is the most common form of breast cancer. Accurately identifying and categorizing
breast cancer subtypes is an important clinical task, and automated methods can be used to
save time and reduce error. To analyze the cellular structures in the breast histology images
we were instead leveraging basic computer vision and image processing algorithms, but
combining them in a novel way. These algorithms worked really well — but also required
quite a bit of work to put together.

The goal of this script is to identify IDC when it is present in otherwise unlabeled
histopathology images. The dataset consists of 277,524 50x50 pixel RGB digital image
patches that were derived from 162 H&E-stained breast histopathology samples. These
images are small patches that were extracted from digital images of breast tissue samples.
The breast tissue contains many cells but only some of them are cancerous. Patches that
are labeled "1" contain cells that are characteristic of invasive ductal carcinoma.
• The dataset was downloaded from Kaggle, breast-histopathology-images.
• Spyder was used as a module to train and test the data.
• The model architecture used was CancerNet taken from Pyimagesearch.
• Preprocessing and data augmentation were carried out on downloaded data.
• The module was first supplied with training split, where the model was trained
and weights were saved and then the accuracy of testing split was tested using CNN
and confusion matrix respectively.
• The training data was processed by applying feature extraction.
The test data obtained was tested for accuracy. The results were noted and recorded for
further analysis.
• The model was also used for making predictions on raw images taken directly from the
internet.
