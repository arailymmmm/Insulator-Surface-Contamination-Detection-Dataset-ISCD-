# Insulator-Surface-Contamination-Detection-Dataset-ISCD-
The Insulator Surface Contamination Detection Dataset (ISCD) provides visible-light images of high-voltage insulators with various surface contamination types. The dataset aims to support the development of machine learning and computer vision models for automatic contamination classification and condition assessment of outdoor insulators.

The original dataset contains 11,816 images, which were expanded to 15,000 images through data augmentation techniques to enhance model robustness and balance class distribution.

The dataset includes six contamination categories:

Clean

Snow

Dust

Wet Dust

Cement Powder

Salt

Each category contains RGB images of polymeric and ceramic insulators captured under different illumination and background conditions. The dataset is organized into two main directories:

images/ — contains the insulator image files.

labels/ — contains the corresponding annotations in VOC2007 format, labeling insulator regions and contamination types.

The dataset was developed as part of research on automated surface contamination detection of high-voltage insulators, conducted to enhance reliability and safety in power transmission systems.

Public subset available here: 500 representative images

Image format: .jpg

Annotation format: YOLO .txt files (each image has a corresponding label file)

If you have any questions regarding this dataset, please contact Arailym Serikbay at arailymserikbay@gmail.com
.
