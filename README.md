# OVERVIEW

Digital radiography is one of the most common and effective standards for diagnosing bone fractures. Such diagnoses typically require the involvement of doctors and medical specialists. With the rapid development of computer vision, the use of models to assist in diagnosis has gained increasing attention. 

Based on the "FracAtlas: A Dataset for Fracture Classification, Localization and Segmentation of Musculoskeletal Radiographs," an important dataset in the field of fracture image classification, we have built models such as AlexNet, VGG, DenseNet, EfficientNet, RepVGG, RegNet, and ResNet to classify fracture images.

# DATASET

FracAtlas is a collection of X-ray images gathered from three major hospitals in Bangladesh. The dataset consists of 4,083 manually annotated images to perform tasks such as fracture classification, localization, and segmentation, with the assistance of two professional radiologists and an orthopedic surgeon. 

The creation of the FracAtlas dataset involved multiple stages, starting with the collection of 14,068 X-ray images, converting them from DICOM to JPG format to ensure privacy. Next, the dataset was filtered to exclude scans unrelated to fractures, except for areas involving the hands, legs, hips, and shoulders. This process resulted in a final dataset of 4,083 images, including 717 fracture images and 3,366 normal bone images.

- Original dataset link: [FracAtlas Dataset](https://figshare.com/articles/dataset/The_dataset/22363012)
- Processed dataset link: [Processed Dataset](https://drive.google.com/drive/folders/1aGVUiNThI2DZ0oEGCu468IGOG_NHKfv8?usp=sharing)
